# HomeWork
HomeWork Zheludin Sergey




using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace My1App
{
    class Program
    {
        static void Main(string[] args)
        {
            //задача 1
            Console.WriteLine("Привет! Введите своё имя: ");
            string name = Console.ReadLine();

            Console.WriteLine("Укажи свою фамилию: ");
            string FirstName = Console.ReadLine();

            Console.WriteLine("Сколько тебе лет?: ");
            int age = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Твой вес?: ");
            double weight = Convert.ToDouble(Console.ReadLine());

            Console.WriteLine("Укажи свой рост, в сантиметрах: ");
            double height = Convert.ToDouble(Console.ReadLine());

            Console.WriteLine($" Имя: {name}\n Фамилия: {FirstName}\n Возраст: {age}\n Вес: {weight}\n Рост: {height}\n ");
            //задача 2
            double box = weight / (height/100 * height/100);

            Console.WriteLine($"Твой индекс массы тела равен: " + "{0:f1}", box );

            //задача 3


            Console.Write("Координата х1 - ");
            int x1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Координата y1 - ");
            int y1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("\nКоордината х2 - ");
            int x2 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Координата y2 - ");
            int y2 = Convert.ToInt32(Console.ReadLine());

            Console.Clear();

            double result = Math.Sqrt(Math.Pow(x2 - x1, 2) + Math.Pow(y2 - y1, 2));

            Console.WriteLine("Расстояние - {0:F}", result);

            //задача 4а


            Console.WriteLine("Введите первое число: ");
            double a = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Введите второе число: ");
            double b = Convert.ToInt32(Console.ReadLine());

            double c = b;
            b = a;
            a = c;
            Console.WriteLine("ваши числа: ");
            Console.WriteLine( a );
            Console.WriteLine( b );

            //задача 4б

            Console.WriteLine("Введите первое число: ");
            double d = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Введите второе число: ");
            double e = Convert.ToInt32(Console.ReadLine());

            d = d + e;
            e = d - e;
            d = d - e;

            Console.WriteLine("ваши числа: ");
            Console.WriteLine(d);
            Console.WriteLine(e);

            Console.ReadKey();


