# Factorial
import java.util.*;
import java.lang.*;
import java.io.*;
class Factorial
{
	public static void main (String[] args) 
	{
		int n,fact=1;
		System.out.println("Enter the no.");
		Scanner s = new Scanner(System.in);
		n=s.nextInt();
		for(int i=n;i>0;i--)
		{
		    fact=fact*i;
		}
		System.out.println("Factorial of the no. is "+fact);
	}
}
