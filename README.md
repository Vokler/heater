# Тепло-электро нагреватель

Симулятор работы ТЭН на языке программирования Ассемблер и JavaScript.

### Описание задачи

Имеется система, позволяющая включать обогрев помещения и регулировать температуру в помещении.

Включение обогрева производится, если температура в помещении ниже заданного уровня. Контроль за температурой
осуществляется датчиком, выдающим 0 или 1. Включение и выключение обогрева – подача напряжения на тэн согласно
рисунку ниже.

В системе также производится измерение влажности с помощью 12 датчиков.
Датчики опрашиваются в следующем режиме: датчики ДВ1, ДВ3, ДВ5 опрашиваются с интервалом 2 с,
датчики ДВ7, ДВ9, ДВ11 с интервалом 4 с, датчики ДВ2, ДВ4, ДВ6 с интервалом 6 с и датчики ДВ8, ДВ10, ДВ12 с интервалом 8 с.

Опрос прекратить, когда в любой группе датчиков измеряемая суммарная влажность не превысит 80%.
Датчики измеряют влажность в диапазоне от 10 до 100%, диапазон выходного сигнала 0,45 - 9,2В.

АЦП 14 разрядов, вх. сигнал 0…10 В.

ЦАП 8 разрядов, вых. сигнал 0…80 В.

<img src="https://i.gyazo.com/ba3004fd8f0d5829274e01a81f031bf5.png" width="40%">

### Функциональная схема

<img src="https://i.gyazo.com/18fd13683dd83e6ea648659566509e89.png" width="60%">

### GUI работы ТЭН

[![Image from Gyazo](https://i.gyazo.com/a31fe2615ba8b175e6267e1237406bfa.gif)](https://gyazo.com/a31fe2615ba8b175e6267e1237406bfa)

