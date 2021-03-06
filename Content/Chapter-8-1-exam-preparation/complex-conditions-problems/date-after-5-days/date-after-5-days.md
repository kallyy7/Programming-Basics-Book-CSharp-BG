### Задача: дата след 5 дни

Дадени са две числа **d** (ден) и **m** (месец), които формират **дата**. Да се напише програма, която отпечатва датата, която ще бъде **след 5 дни**. Например 5 дни след **28.03** е датата **2.04**. Приемаме, че месеците: април, юни, септември и ноември имат по 30 дни, февруари има 28 дни, а останалите имат по 31 дни. Месеците да се отпечатат с **водеща нула**, когато са едноцифрени (например 01, 08).

#### Вход

Входът се чете от конзолата и се състои от два реда:
-	На първия ред стои едно цяло число **d** в интервала [**1 … 31**] – ден. Номерът на деня не надвишава броя дни в съответния месец (напр. 28 за февруари).
-	На втория ред стои едно цяло число **m** в интервала [**1 … 12**] – месец. Месец 1 е януари, месец 2 е февруари, …, месец 12 е декември. Месецът може да съдържа водеща нула (напр. април може да бъде изписан като 4 или 04).

#### Изход

Отпечатайте на конзолата един единствен ред, съдържащ дата след 5 дни във формат **ден.месец**. Месецът трябва да бъде двуцифрено число с водеща нула, ако е необходимо. Денят трябва да е без водеща нула.

#### Примерен вход и изход

|Вход|Изход|Вход|Изход|
|---|---|---|---|
|28<br>03|2.04|27<br>12|1.01|

|Вход|Изход|Вход|Изход|
|---|---|---|---|
|25<br>1|30.01|26<br>02|3.03|
