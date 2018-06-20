##### NB! THIS FIRMWARE IS NOT FOR COMMERCIAL USE!!! DO NOT BUY ANY ESP DEVICE WITH THIS FW - IT'S 3-4 TIMES MORE EXPENSIVE THAN THE DEVICE ITSELF!!! JUST BUY ESP8266 AND FLASH IT BY YOURSELF!!! 

##### NB! ПРЕДСТАВЛЕННАЯ ЗДЕСЬ ПРОШИВКА НЕ ДЛЯ КОММЕРЧЕСКОГО ИСПОЛЬЗОВАНИЯ!!! НЕ ПОКУПАЙТЕ МОДУЛЬ С ДАННОЙ ПРОШИВКОЙ - ОН СТОИТ В 3-4 РАЗА ДОРОЖЕ, ЧЕМ САМО УСТРОЙСТВО!!! ПРОСТО КУПИТЕ ESP8266 И ПРОШЕЙТЕ ЕГО САМОСТОЯТЕЛЬНО!!!

## PS4 Payloads Host Firmware for ESP8266 (OFW 4.55/5.05 autodetected)
## Прошивка ESP8266 для хоста пэйлоадов PS4 (автоопределение ПО 4.55/5.05) (описание на русском смотрите ниже)

Here you can find ESP8266 custom firmware for hosting PS 4 payloads for 4.55/5.05 OFW with autodetection (based on UA check). It is simple and light firmware without any tools like autopayload, firmware upgrade, ftp server for uploading files, etc. 

### 4.55
**The payloads list for 4.55 includes:**

    Original
    HEN
    HEN+VR
    BackUp
    App2USB
    FTP
    FTP+RW
    Dumper
    Disable/Enable Updates
    Enable Browser
    
*Payload version is indicated in "About" section*


**Useful Tips for 4.55:**
1. Best combination for gaming: Original+HEN (load one after another)
2. Best combination for dumper/backup: HEN+Dumper/Backup (load one after another, increases processing speed significantly)
3. HEN in this repo is spoofed. One can play games, dumped on FW >4.55
4. If any payload does not work properly (no notifications, long uploading), just try to reload it


### 5.05
**The payloads list for 4.55 includes:**

    HEN
    MIRA+HEN
    BackUp
    App2Usb
    FTP
    Dumper
    VR
    Bin Loader
    Disable/Enable ReactPS+
    Disable/Enable Updates
    Disable/Enable Blocker EXTREME
    
*Payload version is indicated in "About" section*


**Cache**

Payload can be used in offline mode - just click "CACHE" and all the contents will be cached in PS4 system. Now you can turn off "Connect to the Internet" and run payloads as usually (works via user's guide/browser).


**Useful Tips for 5.05:**
1. 5.05 HEN is unstable in general, you should individually fit together optimal conditions for achieving system stability (waiting some minutes before payload run, closing all apps, navigating in the menu, etc.)
2. VR is to be run if you get a message about updating VR software when you turn VR headset on
3. It's better to create permanent bookmark for offline mode, for example, /13.13.13.1/index.html


### COMMON    
**PS4 Wi-Fi Settings (EASY):**

    Network: PS4
    Password: qwertyuiop

*"Test internet connection" also passes successfully with such settings!*


Upload firmware in .bin format via NodeMCU-PyFlasher 3.0 (added screenshot with NodeMCU-PyFlasher settings in "release" page )

### CREDITS TO:

Al-Azif, Specter, Qwertyoruiopz, Flatz, XVortex, Stooged, LightningMods, Anonymous, Marcelstoer, EdiTzZ, Zer0xFF, The Open Orbis team, etc.



## Прошивка ESP8266 для хоста пэйлоадов PS4 (автоопределение ПО 4.55/5.05)
Данный репозиторий содержит прошивку для модуля ESP8266 с поднятием веб-сервера для хоста эксплоитов/пэйлоадов Playstation 4 с автоопределением ПО 4.55/5.05 (на базе UA check). Данная прошивка отличается простым и легким интерфейсом и не содержит никаких дополнительных утилит, например, автозагрузка пэйлоада, обновление прошивки, ФТП сервер для загрузки файлов и т.д.

### 4.55
**Список пэйлоадов для 4.55 состоит из:**

    Original
    HEN
    HEN+VR
    BackUp
    App2USB
    FTP
    FTP+RW
    Dumper
    Disable/Enable Updates
    Enable Browser
    
*Версия пэйлоада указана в разделе "About"*


**Полезные советы для 4.55:**
1. Наиболее стабильная комбинация для игры: Original+HEN (запускать по очереди)
2. Для Dumper'а/BackUp'а использовать комбинацию: HEN+Dumper/BackUp (запускать по очереди, существенно увеличивается скорость проработки команды)
3. HEN в составе сборки содержит спуф. Возможно запускать игры, которые были сдампены на ПО >4.55.
4. Если и случается ошибка или долгое время ничего не происходит с активацией пэйлоада (нет уведомления), попробуйте просто повторно его запустить


### 5.05
**Список пэйлоадов для 5.05 состоит из:**

    HEN
    MIRA+HEN
    BackUp
    App2Usb
    FTP
    Dumper
    VR
    Bin Loader
    Disable/Enable ReactPS+
    Disable/Enable Updates
    Disable/Enable Blocker EXTREME
    
*Версия пэйлоада указана в разделе "About"*


**Кэш**

Пэйлоады можно использовать в оффлайн режиме - для этого нажмите "CACHE" и все содержимое закэшируется в консоль. Теперь Вы можете отключить "Подключить к интернету" и запускать пэйлоады как обычно (работает через руководство пользователя/браузер).


**Полезные советы для 5.05:**
1. Сам по себе HEN для 5.05 достаточно нестабилен, Вам самим предстоит подобрать наиболее оптимальные условия, при которых достигается общая стабильность системы (подождать пару минут перед запуском пэйлоада, закрыть все приложения, "побродить" по меню и т.д.)
2. Запуск VR необходим в том случае, если при включении VR у Вас выскакивает сообщение о необходимости обновления прошивки
3. Для использования оффлайн режима лучше создать постоянную закладку, например, /13.13.13.1/index.html


### ОБЩИЕ    
**Настройки PS4 Wi-Fi (метод подключения - ПРОСТОЙ):**

    Сеть: PS4
    Пароль: qwertyuiop

*С данными настройками так же успешно проходится тест на подключение к интернету!*

Прошивка предоставляется в формате bin для заливки в модуль с помощью NodeMCU-PyFlasher 3.0 (в разделе "релиз" добавлен скриншот с настройками NodeMCU-PyFlasher)

### ОСОБАЯ БЛАГОДАРНОСТЬ РАЗРАБОТЧИКАМ:

Al-Azif, Specter, Qwertyoruiopz, Flatz, XVortex, Stooged, LightningMods, Anonymous, Marcelstoer, EdiTzZ, Zer0xFF, The Open Orbis team, etc.
