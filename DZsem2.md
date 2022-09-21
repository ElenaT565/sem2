// задача 10
/*int number = new Random().Next(100,1000);
int num1 = number / 10;
int num2 = num1 % 10;

Console.WriteLine($"Вторая цифра рандомного числа {number} = {num2}");*/

//Задача 13

Console.WriteLine($"Введите число");

int number = int.Parse(Console.ReadLine());
if (number >= 999)
{
   while(number > 999)
    {
    
    number = number / 10;
   } 
int num1 = number % 10;

Console.WriteLine($"Третья цифра заданного числа = {num1}");
}

else 

Console.WriteLine($"Третьей цифры в заданном числе нет");

//Задача 15

/*Console.WriteLine($"Введите день недели от 1 до 7");

int num = int.Parse(Console.ReadLine());

if (num < 6)
Console.WriteLine($" День номер {num} - рабочий");

else 
Console.WriteLine($"День номер {num} - выходной");*/