# DCIT-318--Assignment-10823856 ( grade calculator) 


using System;

namespace GradeCalculator
{
    class Program
    {
        static void Main(string[] args)
        {
            
            Console.Write("Enter the numerical grade scored (0-100): ");
            int grade = int.Parse(Console.ReadLine());

            char letterGrade;

           
            if (grade >= 90)
            {
                letterGrade = 'A';
            }
            else if (grade >= 80)
            {
                letterGrade = 'B';
            }
            else if (grade >= 70)
            {
                letterGrade = 'C';
            }
            else if (grade >= 60)
            {
                letterGrade = 'D';
            }
            else
            {
                letterGrade = 'F';
            }

            
            Console.WriteLine("The letter grade is: " + letterGrade);
        }
    }
}

