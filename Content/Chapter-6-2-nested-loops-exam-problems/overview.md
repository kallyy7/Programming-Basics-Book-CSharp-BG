# Глава 6.2. Вложени цикли – изпитни задачи

В предходната глава разгледахме **вложените цикли** и как да ги използване за **рисуване** на различни **фигури на конзолата**. Научихме се как да отпечатваме фигури с различни размери, измисляйки подходяща логика на конструиране с използване на **единични и вложени `for`** цикли в комбинация с различни изчисления и програмна логика:

```csharp
for (var r = 1; r <= 5; r++)
{
   Console.Write("*");
   for (var c = 1; c < 5; c++)
      Console.Write(" *");
   Console.WriteLine();
}
```

Запознахме се и с **конструктора `new string`**, който дава възможност да се печата **даден символ определен** от нас **брой** пъти:

``` csharp
string printMe = new string('*', 5);
```
