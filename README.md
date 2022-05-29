# C-GradingSystem-Console




using System;
using System.Linq;

namespace Gradingsystem
{
	public static class Program
	{
		public static void Main()
		{
			
Console.Write("1st Grading:");
double a = Convert.ToDouble(Console.ReadLine());

Console.Write("2nd Grading:");
double b = Convert.ToDouble(Console.ReadLine());

Console.Write("3rd Grading:");
double c = Convert.ToDouble(Console.ReadLine());

Console.Write("4th Grading:");
double d = Convert.ToDouble(Console.ReadLine());
double e = 4; 
double final = (a + b + c + d) / e;
Console.WriteLine("Your Final Grade Is " + final);
		}
	}
}
