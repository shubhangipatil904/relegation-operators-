# relegation-operators-
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public class Program 
    {
        public static void Main()
        {
        	int a,b,c;
        	Console.WriteLine("Enter No 1");
        	a=Convert.ToInt32(Console.ReadLine());
        	Console.WriteLine("Enter No 1");

        	b=Convert.ToInt32(Console.ReadLine());
        	c=a+b;
        	Console.WriteLine("The Addition "+c);
        		c=a-b;
        		Console.WriteLine("The Subtraction "+c);

            	c=a*b;
        	Console.WriteLine("The Multiplication "+c);
        	c=a/b;

        	Console.WriteLine("The Division "+c);
		
			c=a%b;
			Console.WriteLine("The Modulation"+c);
		
        }
    }
}
Output :-
Enter No 1
5
Enter No 1
9
The Addition 14
The Subtraction -4
The Multiplication 45
The Division 0
The Modulation5
 
