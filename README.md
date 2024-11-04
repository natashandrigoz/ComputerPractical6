# **Компьютерный практикум 6**
## Решение задач
### Задача №1
#### Условие:
Запрашивает с клавиатуры два целых числа и выводит на экран сумму данных чисел:

![](https://i.postimg.cc/G2cC1TjK/2024-11-03-233858.png)
#### Решение:
```C#
namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            int a = int.Parse(Console.ReadLine());
            Console.Write("b=");
            int b = int.Parse(Console.ReadLine());
            Console.WriteLine($"{a}+{b}={a+b}");
            Console.Read();
        }
    }
}
```
___
### Задача №2
#### Условие:
Запрашивает с клавиатуры два целых числа, и выводит на экран сумму данных чисел в прямом и обратном порядке:

![](https://i.postimg.cc/NFmS9gbF/2024-11-03-235428307.png)
#### Решение:
```C#
namespace ConsoleApp2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            int a = int.Parse(Console.ReadLine());
            Console.Write("b=");
            int b = int.Parse(Console.ReadLine());
            Console.WriteLine($"{a}+{b}={b}+{a}");
            Console.Read();
        }
    }
}
```
___
### Задача №3
#### Условие:
Запрашивает с клавиатуры два вещественных числа, и выводит на экран произведение данных чисел (веществе запятонные числа выводятся с точностью до 1 знака послей):

![](https://i.postimg.cc/R0PB4Vbz/2024-11-03-235238743.png)
#### Решение:
```C#
namespace ConsoleApp3
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            double a = double.Parse(Console.ReadLine());
            Console.Write("b=");
            double b = double.Parse(Console.ReadLine());
            Console.WriteLine($"{a:F1}*{b:F1}={a*b:F1}");
            Console.Read();
        }
    }
}
```
___
### Задача №4
#### Условие:
Запрашивает с клавиатуры три вещественных числа, и выводит на следующее сообщение (вещественные числа выводятся с точностью до 2 знаков после запятой):

![](https://i.postimg.cc/Y2dmZ1xX/2024-11-03-235722429.png)
#### Решение:
```C#
namespace ConsoleApp4
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            double a = double.Parse(Console.ReadLine());
            Console.Write("b=");
            double b = double.Parse(Console.ReadLine());
            Console.Write("c=");
            double c = double.Parse(Console.ReadLine());
            Console.WriteLine($"({a:F2}+{b:F2})+{c:F2}={a:F2}+({b:F2}+{c:F2})");
            Console.Read();
        }
    }
}
```
___
### Задача №5
#### Условие:
Запрашивает с клавиатуры четыре вещественных числа, и выводит на экран результат деления первого числа на второе плюс третьего на четвертое (вещественные числа выводятся с точностью до 2 знаков после запятой):



![](https://i.postimg.cc/cH11RwWn/2024-11-04-151950209.png)
#### Решение:
```C#
namespace ConsoleApp5
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            double a = double.Parse(Console.ReadLine());
            Console.Write("b=");
            double b = double.Parse(Console.ReadLine());
            Console.Write("c=");
            double c = double.Parse(Console.ReadLine());
            Console.Write("d=");
            double d = double.Parse(Console.ReadLine());
            Console.WriteLine($"{a:F2}/{b:F2}+{c:F2}/{d:F2}={(a / b + c / d):F2}");
            Console.Read();
        }
    }
}
```
___
### Задача №6
#### Условие:
Запрашивает с клавиатуры два целых числа, и выводит на экран результат их суммы, разности и произведения:

![](https://i.postimg.cc/VkVNc4xL/2024-11-04-154522792.png)
#### Решение:
```C#
namespace ConsoleApp6
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            int a = int.Parse(Console.ReadLine());
            Console.Write("b=");
            int b = int.Parse(Console.ReadLine());
            Console.Write($"a+b={a}+{b}={a + b}");
            Console.Write($"  a-b={a}-{b}={a - b}");
            Console.Write($"  a*b={a}*{b}={a * b}");
            Console.Read();
        }
    }
}
```
___
### Задача №7
#### Условие:
Запрашивает с клавиатуры три целых числа и выводит следующее сообщение [a*(b+c)]=[(b+c)*a]:

![](https://i.postimg.cc/63YZnC77/2024-11-04-162719900.png)
#### Решение:
```C#
namespace ConsoleApp7
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            int a = int.Parse(Console.ReadLine());
            Console.Write("b=");
            int b = int.Parse(Console.ReadLine());
            Console.Write("c=");
            int c = int.Parse(Console.ReadLine());
            Console.WriteLine($"[{a}*({b}+{c})]=[({b}+{c})*{a}]={a*(b+c)}");
            Console.Read();
        }
    }
}
```
___
### Задача №8
#### Условие:
Запрашивает с клавиатуры три вещественных числа и выводит следующее сообщение (a+(b+c))=(a+c+b) (вещественные числа выводятся с точностью до 4 знаков после запятой):

![](https://i.postimg.cc/VLytMsvW/2024-11-04-163347058.png)
#### Решение:
```C#
namespace ConsoleApp8
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            double a = double.Parse(Console.ReadLine());
            Console.Write("b=");
            double b = double.Parse(Console.ReadLine());
            Console.Write("c=");
            double c = double.Parse(Console.ReadLine());
            Console.WriteLine($"({a:F4}+({b:F4}+{c:F4})=({a:F4}+{b:F4}+{c:F4})");
            Console.Read();
        }
    }
}
```
___
### Задача №9
#### Условие:
Утраивает значение вещественной переменной х и выполняет деление на целое число y, результат округлить до 4 знаков после запятой:

![](https://i.postimg.cc/wxQf4rNJ/2024-11-04-162211185.png)
#### Решение:
```C#
namespace ConsoleApp9
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("x=");
            double x = double.Parse(Console.ReadLine());
            Console.Write("y=");
            int y = int.Parse(Console.ReadLine());
            Console.WriteLine($"{x * 3}/{y}={(x * 3 / y):F4}");
            Console.Read();
        }
    }
}
```
___
### Задача №10
#### Условие:
Запрашивает с клавиатуры два вещественных числа, и выводит на экран результат их умножения друг на друга в два столбика: первый столбик – вывод результата с точностью 3 знака после запятой, второй столбик – с точностью 5 знаков после запятой:

![](https://i.postimg.cc/ydbF2F7M/2024-11-04-165108829.png)
#### Решение:
```C#
namespace ConsoleApp10
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("a=");
            double a = double.Parse(Console.ReadLine());
            Console.Write("b=");
            double b = double.Parse(Console.ReadLine());
            Console.WriteLine($"a*b={a:F3}*{b:F3}={a*b:F3}   a*b={a:F5}*{b:F5}={a*b:F5}");
            Console.Read();
        }
    }
}
```
