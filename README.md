# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
```
Start the program and declare the variables required.
Obtain the input from the user and read the values.
Calculate the total marks and check for the conditions.
Print the required output.
End the program
```

## Program:
```
NAME:KATHIRVEL.A
REG NO:212221230047
```
```
using System;

namespace EngineeringAdmission
{
    class Program
    {
        static void Main(string[] args)
        {
            int maths, physics, chemistry;
            Console.WriteLine("Welcome to Engineering Admission Eligibility Checker");

            Console.Write("Enter Math marks: ");
            maths = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Physics marks: ");
            physics = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Chemistry marks: ");
            chemistry = Convert.ToInt32(Console.ReadLine());

            int totalMarks = maths + physics + chemistry;

            if (maths >= 65 && physics >= 55 && chemistry >= 50)
            {
                if (totalMarks >= 180)
                {
                    Console.WriteLine("Congratulations! You are eligible for admission.");

                }
                else
                {
                    Console.WriteLine("Sorry, you are not eligible for admission.");

                }
            }
        }
    }
}
```



## Output:



![image](https://github.com/KathirvelAIDS/Eligibility-for-Admission/assets/94911373/69ff13f4-eae4-4fb7-a8eb-ef2ee431351d)



## Result:




Thus a C# program to find the eligibility for admission to an engineering course is written and executed.
