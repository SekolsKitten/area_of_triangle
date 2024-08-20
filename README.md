using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Area_of_Triangle
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Calculate Area of triangle
            //Take user input for base
            //Take user input for height
            // Run calculation and output are
            // areaOfTriangle = .5 * Base64FormattingOptions * height
            Console.WriteLine("Welcome to my Area of Triangle Calculator App");
            Console.WriteLine("Please enter the length of the base:");
            double triBase = double.Parse(Console.ReadLine());
            Console.WriteLine("Please enter the length of the base:");
            double triHeight = double.Parse(Console.ReadLine());
            double areaOfTri = .5 * triBase * triHeight;

            Console.WriteLine($"The area of a trianlge is: {areaOfTri} ");



            Console.ReadLine();
        }
    }
}****
