# Sonoff Homekit

Эта прошивка делает Sonoff Basic совместимым с Apple Homekit !

<img src="https://github.com/Batyushin/Sonoff-HomeKit/blob/master/pic/sonoffonly.png" alt="Sonoff" width="180"/>
<img src="https://github.com/Batyushin/Sonoff-HomeKit/blob/master/pic/homekit.png" alt="Works with Apple Homekit" width="180"/>

### Homekit работает на Sonoff! 😳

В отличие от других проектов на github, эта прошивка НЕ требует Вам установки HomeBridge, работающий на Raspberry-Pi или MQTT, достаточно Wi-Fi-соединения и устройства Apple!

Apple предоставила спецификации разработчикам, поэтому это стабильное и поддерживаемое программное обеспечение, и оно будет продолжать работать в течение длительного времени.

Теперь вы, наконец, можете иметь устройства HomeKit, не тратя много денег!

### Совместимые устройства
Это программное обеспечение в настоящее время протестировано на: Sonoff Basic, 

## Инструкция

### Прошивка Sonoff
 1) Отключите ваш sonoff от линии электропитания
 2) Соедините Sonoff с последовательным адаптером по 3.3v
 3) Запустить firmware/ESP8266Flasher.exe

### Добавляем Sonoff в приложение Дом
 1) Открываем настройки -> Wi-Fi на Вашем iPhone или iPad  
 2) Подключаемся к сети с именем: `Sonoff Switch-xxx`
 3) Вибираем из перечня Свой домашний роутер, вводим пароль и нажимаем кнопку `Join`
 4) Открываем приложение Дом
 5) Нажимаем `+` -> `Добавить аксессуар`
 6) Нажимаем  `Нет кода или не можете сканировать?`
 7) Вибираем переключатель Sonoff-xxx Switch 
 8) Пароль сопряжения `888-88-888`

Готово! 🎉 

## Если Вам понравился этот проект:

Номер кошелька: <b>410011714800830</b>
<img src="https://github.com/Batyushin/Sonoff-HomeKit/blob/master/pic/donate.jpg" alt="Sonoff" width="180"/>



---

#### Особая благодарность:
@maximkulkin

This project would not have existed without:
https://github.com/maximkulkin/esp-homekit
https://github.com/maximkulkin/esp-homekit-demo
https://github.com/maximkulkin/esp-wifi-config

