# COWBOY
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp3
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Введите число");
            string number = Console.ReadLine();
            double NumberS;
            bool parsed = Double.TryParse(number, out NumberS);

        
            double z = NumberS % 2;

            
            
            if (z > 0)
            {
                Console.WriteLine("Вы ввели нечетное число");
            }
            if (z == 0)
            {
                Console.WriteLine("Вы ввели четное число ");
            }
            if (number.Equals("0"))
            {
                Console.WriteLine("Вы ввели нуль");

                
            }
            Console.ReadLine();
