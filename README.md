# Small-class-project
Calculating the radius, diameter and area of a circle

//Momin Hussain
//COP3223c Sping2018
//HW1 Problem 2
#include <stdio.h>

int main ()
{
 int radius;

 //Prompt user and obtain inputs
 printf("Enter the radius of a circle as an integer: ");
 scanf("%d", &radius);

 //Calculate and print solution
 printf("For a circle with radius: %d\n", radius);
 printf("Diameter = %d\n", (radius + radius) );
 printf("Circumference = %f\n", 2 * 3.14159 * radius );
 printf("Area = %f \n", 3.14159 * radius * radius );

 return 0;
}
//End of Problem 2
