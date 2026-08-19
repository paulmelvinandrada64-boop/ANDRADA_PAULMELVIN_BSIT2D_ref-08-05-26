# ANDRADA_PAULMELVIN_BSIT2D_ref-08-05-26
using System;

public class Helloworld
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Enter your name: ");
        string name = Console.ReadLine();

        Console.WriteLine("Enter your age: ");
        int age = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine("Enter your weight in kg: ");
        double weightkg = Convert.ToDouble(Console.ReadLine());

        double math = Math.Round(weightkg, 2); 
        bool isStudent = true;

    
        Console.WriteLine("Hello " + name + ", you are " + age + " years old, your weight is " 
                          + math.ToString("F2") + " kg, and you are a student: " + isStudent);
    }
}

using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        string myString = "Paul Melvin Andrada";
        int myInt = 19;
        double myFloat = 50 + 0.5;
        bool myBoolean = true;

        Console.WriteLine(myInt);
        Console.WriteLine(myString);
        Console.WriteLine(myFloat);
        Console.WriteLine(myBoolean);
    }
}
