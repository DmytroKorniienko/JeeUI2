# JeeUI2
JeeUI Framework v2

Внимание, относительно базовой версии фреймворк переработан.
Главное отличие - для нормальной работы обязательно требуется поместить файлы CSS/JS/index в файловую систему ESP8266/ESP32.
Все необходимое для этого находится в JeeUI2\templates\data\ в виде gzip, именно в таком виде и должно быть помещено в ФС, с сохранением структуры каталогов
Сделать это можно из PlatformIO c помощью PlatformIO->Run Task...->Upload File System Image

Подробнее о доработках и текущем статусе можно почитать в данной теме: https://community.alexgyver.ru/threads/wifi-lampa-budilnik-proshivka-firelamp_jeeui-gpl.2739/
