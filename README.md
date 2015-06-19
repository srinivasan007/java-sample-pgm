# java-sample-pgm
below the program created by srini
import java.util.Scanner;
class if_else
{
	
 static void display(int a,int b)
{
	int x=a;
	int y=b;
	if(x>y)
	{
		System.out.println(x);
	}
	else
	{
	System.out.println(y);
	}	
}
}





class testno
{
public static void main(String args[])
{
Scanner s=new Scanner(System.in);
System.out.println("enter the value of a:");
int a=s.nextInt();
System.out.println("enter the value of b:");
int b=s.nextInt();
if_else.display(a,b);
}
}
