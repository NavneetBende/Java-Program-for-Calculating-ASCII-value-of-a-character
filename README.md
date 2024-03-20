ASCII Value of a character using Java
Here, in this page we will discuss the program to print ASCII value of a character using java. ASCII value can be any integer number between 0 and 127 and consists of character variable instead of the character itself in Java programming.

ASCII value of a character using java
Did you know?
 ASCII stands for American Standard Code for Information Interchange
Which is a binary code used by electronic equipment for electronic communications
A total of 128 characters have been assigned values from 0 – 127
Alphabets (  65 – 90  &  97 – 122  )
Digits (  48 – 57  )
Remaining are Special Character (  !, @, #, $, * …..)
Working
User gives an input
Input is stored in a char type variable say val.
val is converted from char to int .
The ASCII value of Character is Obtained
ASCII value of a character
C code
Run
//Java program to print ASCII values of a character

import java.util.Scanner;
class Main
{
	public static void main(String[] args)
	{
		//scanner class object creation
		
		char c='A';	
		
		//typecasting from character type to integer type
		int i = c;
		
		//printing ASCII value of the character
		System.out.println("ASCII value of "+c+" is "+i);
		
		
	}
}
Output
ASCII value of A is 65
