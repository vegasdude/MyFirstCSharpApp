# 🚀 MyFirstCSharpApp

A simple **C# console application** created as my first GitHub project.  
This project demonstrates basic C# syntax, user input, and console output.

---

## 🧠 Features

- Prints a welcome message  
- Takes user input (your name)  
- Displays the current date and time  
- Waits for any key before closing  

---

## 🧩 Code Example

```csharp
using System;

namespace MyFirstCSharpApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("🚀 Welcome to My First C# GitHub Project!");
            Console.Write("Enter your name: ");
            string name = Console.ReadLine();

            Console.WriteLine($"Hello, {name}! This is your first GitHub C# program.");
            Console.WriteLine("Today's date and time: " + DateTime.Now);
            
            Console.WriteLine("\nPress any key to exit...");
            Console.ReadKey();
        }
    }
}
