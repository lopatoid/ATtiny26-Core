# ATtiny26 core for Arduino IDE
 **Версия 1.0.0 от 22.07.2022**  
 Быстрое и легкое ядро, позволяющее программировать недорогие микроконтроллеры ATtiny26 в среде Arduino IDE.
 Включает в себя все основные wiring-функции, пресеты для AVR-программаторов, гибкие настройки и несколько полезных библиотек.
 
## Установка
### Автоматическая
- Открой Arduino IDE
- Зайди в **Файл > Настройки**
- Вставь этот адрес в **Дополнительные ссылки для менеджера плат**:
    ```
    https://nich1con.github.io//ATtiny26-Core.json
    ``` 
- Открой **Инструменты > Плата > Менеджер плат...**
- Подожди загрузку списка
- Листай в самый низ, пока не увидишь **ATtiny26-Core**
- Жми **Установка**
- Закрой окно
- Выбери плату в **Инструменты > Плата > ATtiny26-Core > ATtiny26**
- Готово!

### Ручная
- Папку ATtiny26-Core положить по пути C:\Users\Username\Documents\Arduino\hardware 
- Если папка hardware отсутствуют - необходимо создать ее.

## Раписновка ATtiny26 и доступные wiring-функции
### Используя данное ядро придерживайтесь этой распиновки:
![CORE_PINOUT](https://github.com/Nich1con/ATtiny26-Core/blob/main/ATtiny26-pinout.png)
### В ядре реализованы следующие wiring-функции:
- **pinMode(pin, mode)**
- **digitalRead(pin)**
- **digitalWrite(pin, state)**
- **analogRead(pin)**
- **analogWrite(pin, state)**
- **analogReference(reference)**
- **analogPrescaler(prescaler)**

- **millis()**
- **micros()**
- **delay(ms)**
- **delayMicroseconds(us)**

- **attachInterrupt()**
- **detachInterrupt()**
- **shiftOut()**
- **shiftIn()**

- **random(), map() ** и другие математические функции и макросы Arduino