# sum-of-odd-and-even-numbers
Program to find Sum of Even and Odd Numbers from 1 to n.

This program allows the user to enter the maximum limit value. Next, this C program calculate the sum of even and odd numbers between 1 and the maximum limit value.

if ( number % 2 == 0 )
Any number that is completely divisible 2 is even number. If condition check whether the remainder of the number divided by 2 is exactly equal to 0 or not.

If the condition is True, it is Even number.
If the condition is False, it is an Odd number.


#include<stdio.h>
 
int main()
{
  int i, number, Even_Sum = 0, Odd_Sum = 0;
 
  printf("\n Please Enter the Maximum Limit Value : ");
  scanf("%d", &number);
  
  for(i = 1; i <= number; i++)
  {
  	if ( i%2 == 0 ) 
  	{
        Even_Sum = Even_Sum + i;
  	}
  	else
  	{
  		Odd_Sum = Odd_Sum + i;
	}
  }
  printf("\n The Sum of Even Numbers upto %d  = %d", number, Even_Sum);
  printf("\n The Sum of Odd Numbers upto %d  = %d", number, Odd_Sum);

  return 0;
}


for(i = 1; i <= number; i++)
In the Next line, We declared the If statement

if ( number % 2 == 0 )
Any number that is divisible by 2 is Even number. If condition will check whether the remainder of the number divided by 2 is equal to 0 or not.

If the condition is True, then it is an Even number, and the C Programming compiler will add i value to Even_Sum.
If the condition is False, then it is an Odd number, the compiler will add i value to Odd_Sum
