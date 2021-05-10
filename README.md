# java-
# Assignment-
1.	JAVA PROGRAM 

import java.util.Scanner; 
public class Area_Perimeter 
{ 
public static void main(String[] args) 
{ 
int L, B, Peri, Area; 

Scanner d = new Scanner(System.in); 

System.out.print("Enter length of rectangle:"); 
L = d.nextInt(); 

System.out.print("Enter breadth of rectangle:"); 
B = d.nextInt(); 

Peri = 2 * (L + B); 
System.out.println("Perimeter of rectangle:"+ Peri); 

area = L * B; 
System.out.println("Area of rectangle:"+ Area); 
} 
}


    2.	Python PROGRAM 

L = int(input("Length : ")) 
W = int(input("Width : "))
 
Area = (L * W)
Perimeter=2*(L + W)
 
print("Area of Rectangle : ",Area) 
print("Perimeter of Rectangle : ",Perimeter)

      3.C# SHARP PROGRAM 

class Program 
{ 
static void Main(string[] args) 
{ 

double length, breadth, Area,Peri; 

Console.WriteLine("Enter the length of rectangle : "); 
length = Convert.ToDouble( Console.ReadLine()); 
Console.WriteLine("Enter the breadth of rectangle : "); 
breadth = Convert.ToDouble(Console.ReadLine()); 

Area = length * breadth; 
Peri = 2(length + breadth); 

Console.WriteLine("\nArea of rectangle: " + Area); 
Console.WriteLine("\nPerimeter of rectangle: " + Peri); 
Console.ReadKey(); 
} 
}
