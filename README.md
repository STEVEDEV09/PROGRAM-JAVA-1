# PROGRAM-JAVA-1
//program to add two number by giving value to compiler 

package allprograms;

public class main {

	public static void main(String[] args) 
	{
		//declaring variable and there value 
		int a=40; 
		int b=80;
		//declaring another variable to store formula(not necessary)
		//we can also write in print function  like a+b after "(double inverted commas)
		int c=a+b;
		System.out.println("Sum of a and b : "+c);
	

	}

}

//program to add two number of taking input from user 
package allprograms;
//importing scanner to scan values 
import java.util.Scanner;
public class main {
	public static void main (String [] args)
	{
		//declaring variable and there value 
		int a,b,sum;
		
		Scanner sc=new Scanner (System.in);
				System.out.println(" Enter first number ");
				//storing values of a variable
		a=sc.nextInt();
		System.out.println(" Enter second number ");
		//storing values of b variable

		b=sc.nextInt();
		//declaring another variable to store formula(not necessary)
		//we can also write in print function  like a+b after "(double inverted commas)
		sum=a+b;
		//printing output in print function 
		System.out.println("Sum of two number is "+sum);
	}
}
