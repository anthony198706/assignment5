# assignment5
#Java based assignment
#Create Your Own Application
#1. use math,
#2. take input from the user
#3. use time/timestamps
#4. output results to the screen 


package assignment;
import java.sql.Timestamp;
import java.util.Date;
import java.util.Scanner;


public class timestamp {
	public static void main(String args[])
{
	int Number1;
	int Number2;
	int Answer;
	
	Scanner in = new Scanner(System.in);
	
	java.util.Date date = new java.util.Date();
	System.out.println(new Timestamp(date.getTime()));
		
	System.out.println("Enter a number that you would like to add to another number. ");
	Number1 = in.nextInt();
	System.out.println("You entered " + Number1);
	
	System.out.println("Enter the second number that you would like to add. ");
	Number2 = in.nextInt();
	System.out.println("The second number you entered is " + Number2);
	Answer = Number1 + Number2;
	
	System.out.println("The first number you entered plus the second number you entered is: " + Answer);
	
}
}
