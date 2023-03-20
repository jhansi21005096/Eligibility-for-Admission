# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
Step 1:

Create a new Class.

Step 2:

Create variable of respective data types to store marks.

Step 3:

Calculate the total for all the three subjects and store it.

Step 4:

Calculate the total for two subjects and store it.

Step 5:

Marks in maths >= 65 & Marks in physics >=55 & Marks in chemistry >=50 Total marks in all three subjects >= 180 or total in maths and physics >= 140

Step 6:

Using Nested if check whether the person is eligible or not for admission based on given conditions.

Step 7:

Print whether the person is eligible or not with the given inputs.

Step 7:

End the Program.


## Program:
using System;

namespace ConsoleApp16

{

    class Program
    
    {
    
        static void Main(string[] args)
        
        {
        
            int phy, math, chem, total1, total2;
            
            string name;
            
            Console.WriteLine("Enter the student name : ");
            
            name = Console.ReadLine();
            
            Console.WriteLine("Enter the physics marks : ");
            
            phy = Convert.ToInt32(Console.ReadLine());
            
            Console.WriteLine("Enter the chemistry mark : ");
            
            chem = Convert.ToInt32(Console.ReadLine());
            
            Console.WriteLine("Enter the Math marks : ");
            
            math = Convert.ToInt32(Console.ReadLine());
            
            total1 = math + phy + chem;
            
            total2 = math + phy;
            
            if(math>=65 && phy>=55 && chem >= 50)
            
            {
            
                if(total1>=180 && total2 >= 140)
                
                {
                
                    Console.WriteLine(name + "is eligible for engineering admission");
                    
                }
                
            }
            
            else
            
            {
            
                Console.WriteLine(name + "is not eligible for engineering admission");
                
            }
            
        }
        
    }
    
}





## Output:



## Result:
C# program is done to find the eligibility for admission to an engineering course and has been successfully executed.
