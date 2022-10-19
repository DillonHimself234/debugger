using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace debugger
{
    class Program
    {
        static void Main(string[] args)
        {
            DebugMePlease();
        }


        static void DebugMePlease()
        {
            // <-- Slashes are for comments


            //Common Data Types
            int myInt = 1347;
            char myChar = 'X';
            float myFloat = 75.32F;
            double myDouble = 123.456789012345;
            double myDecimal = 1234567890.1234567890123456789012345678901234567890;
            bool myBool = true;
            string myString = "Hi. This is just some random text about ninjas. They're pretty awesome. 12345.";



            //Output statement should output the variables listed abve.
            //Comment - This is the Output Statements;
            Console.WriteLine("myInt equals: " + myInt);
            Console.WriteLine("myChar equals: " + myChar);
            Console.WriteLine("myFloat equals: " + myFloat);
            Console.WriteLine("myDouble equals: " + myDouble);
            Console.WriteLine("myDecimal equals: " + myDecimal);
            Console.WriteLine("myBool equals: " + myBool);
            Console.WriteLine("myString equals: " + myString);

            //Input
            Console.ReadLine();
            Console.WriteLine("What is your favorite food? (Press enter when done)");
            string myNewString = Console.ReadLine();
            // Code below should output users favorite food.
            Console.WriteLine("Hey, Here's what you wrote:  + myNewString");

            //Number Inputs
            Console.WriteLine("What is your age? (Press enter when done)");
            string yourAge = Console.ReadLine();
            Console.WriteLine("Hey, Here's your age: " + yourAge);
        }
    }
}
