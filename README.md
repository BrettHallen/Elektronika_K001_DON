# Электроника К 001 ДОН<br>Elektronika K 001 DON
Information about the Specialist-compatible constructor kit computer manufactured in Rostov-on-Don (Ростов-на-Дону) in the Russian SFSR by [ПАО "ГРАНИТ" (Granite)](https://www.paogranit.ru/) in the late 1980s.

![Elektronika logo](/Images/Elektronika_K001_DON_Logo.jpg)

![Elektronika computer](/Images/Elektronika_K001_DON_Computer_small.png)

The blurb on the top of the box says the following:<br>
> Набор "Конструктор" Персональной микро-ЭВМ<br>
>
> Набор-конструктор микро-ЭВМ:<br>
> 1. Для сборки микро-ЭВМ;
> 2. Для ознакомления с устройством микро-ЭВМ;
> 3. Для ознакомления с основами компьютерной техники.<br>
>
> Собранная микро-ЭВМ:
> 1. Обучает по разным общеобразовательным и специальным программам;
> 2. Решает задачи в режиме программируемого калькулятора;
> 3. Реализует разнообразные программы интеллектуальных игр;
> 4. Хранит составленный Вами банк данных.

In English:<br>
> Kit "Constructor" Personal Microcomputer<br>
>
> Microcomputer Constructor Kit:<br>
> 1. For assembling a microcomputer;
> 2. For familiarising yourself with the structure of a microcomputer;
> 3. For familiarising yourself with the basics of computer technology.
>
> Assembled microcomputer:
> 1. Provides training using various general education and specialised programs;
> 2. Solves problems in programmable calculator mode;
> 3. Runs a variety of intellectual game programs;
> 4. Stores the database you have created.

## Firmware
A dump of the КС573РФ2 (2716 analogue) EPROM.<br>

This has some minor differences with the original C000 Loader binary for the [Specialist](/Specialist_Information/Firmware).<br>

## [Power](/Elektronika_K001_DON_Power)
This appears to be the pinout for the 5-pin DIN power socket:
- Pin 1 = +12V regulated
- Pin 2 = ground (общий)
- Pin 3 = +5V regulated
- Pin 4 = -5V unregulated
- Pin 5 = -5V unregulated

![Power pinout](/Images/Elektronika_K001_DON_Power_Pinout_small.png)

I have created a simple replacement that uses a regulated +12VDC power supply and generates regulated ±5V output.<br>

![Elektronika Power Supply](/Elektronika_K001_DON_Power/Elektronika_K001_DON_Power_3D.png)

## [Replacement Keyboard](/Elektronika_K001_DON_Keyboard)
The keyboard is a pretty neat design for the time, nice & simple.  Luckily it is quite easy to replace so here is my attempt using Cherry MX key switches.<br>

Interestingly the Specialist design has a row of function keys along the top: HELP, EDIT, RUN, etc.<br>

These aren't labelled on the K001 DON but they should function - I have included them.<br>

![Original keyboard layout](/Images/Elektronika_K001_DON_Keyboard_1_small.png)

![Replacement keyboard layout](/Elektronika_K001_DON_Keyboard/Specialist_Keyboard_Layout.jpg)

![Replacement keyboard](/Elektronika_K001_DON_Keyboard/Elektronika_K001_DON_Keyboard_3D.png)

### Special Keys
There are some Soviet-specific keys on the keyboard - here is my rough understanding:
- НР = Нижний Регистр (lower case/register)
- НР ФИКС = Нижний Регистр Fix (shift lock)
- ЗБ = Забой (backspace)
- ПС = Перевод Строки (line feed)
- ПВ = Повтор/Вставка (auto-repeat)
- ВК = Возврат Каретки (carriage return)
- СБР = Сброс (reset)

## [Specialist Information](/Specialist_Information)
A great source of information about the Specialist design can be found on [Alexey's retro computer repository](https://github.com/alemorf/retro_computers).<br>

I have copied some of the useful information such as the original firmware and "Modelist Constructor" magazine articles.<br>
