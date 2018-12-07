# Sonoff Homekit

Эта прошивка делает Sonoff Basic совместимым с Apple Homekit !

<img src="https://raw.githubusercontent.com/Gruppio/Sonoff-Homekit/images/images/sonoffonly.png" alt="Sonoff" width="180"/>
<img src="https://raw.githubusercontent.com/Gruppio/Sonoff-Homekit/images/images/transparent.png" alt=" " width="20"/><img src="https://raw.githubusercontent.com/Gruppio/Sonoff-Homekit/images/images/homekit.png" alt="Works with Apple Homekit" width="180"/>

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

## Если вам нравится этот проект:

<img src="" alt="Sonoff" width="180"/>

<iframe src="https://money.yandex.ru/quickpay/shop-widget?writer=buyer&targets=&targets-hint=%D0%9D%D0%B0%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%3A%20%D0%BD%D0%B0%20%D1%80%D0%B0%D0%B7%D0%B2%D0%B8%D1%82%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0&default-sum=&button-text=11&payment-type-choice=on&mobile-payment-type-choice=on&hint=&successURL=&quickpay=shop&account=410011714800830" width="423" height="227" frameborder="0" allowtransparency="true" scrolling="no"></iframe>


---

#### Особая благодарность:
@maximkulkin

This project would not have existed without:
https://github.com/maximkulkin/esp-homekit
https://github.com/maximkulkin/esp-homekit-demo
https://github.com/maximkulkin/esp-wifi-config

