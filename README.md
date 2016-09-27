# Timo-s-project
Task`6
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Globalization;
using System.Threading;
using System.Threading.Tasks;

namespace ConsoleApplication2
{
    class Program
    {
        static void Main(string[] args)
        {   // changing delimiter
            Thread.CurrentThread.CurrentCulture = new CultureInfo("en-US");
            int yourChoice = -1;
            do
            {
                Console.WriteLine("Geometry Calculator\n");
                Console.WriteLine("\t1. Computing the area of a geometric simple circle");
                Console.WriteLine("\t2. Computing the area of a geometric simple Regtangle");
                Console.WriteLine("\t3. Computing the area of a geometric simple Triangle");
                Console.WriteLine("\t4. Computing the area of a geometric simple Quit");
                Console.Write("\tEnter your choice, dude:");
                string receivedValue = Console.ReadLine();
                while (!Int32.TryParse(receivedValue, out yourChoice) || yourChoice < 1 || yourChoice > 4)
                {
                    Console.Write("Not a valid number, try again");
                    receivedValue = Console.ReadLine();
                }
                switch (receivedValue)
                {
                                 

                }

                
               
                

                
             
                // Now comes the switch structure .|.



            } while (yourChoice != 4);
        }
    }
}
