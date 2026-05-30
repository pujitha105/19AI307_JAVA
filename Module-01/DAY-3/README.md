# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To write a java Program to print square of the value.

## ALGORITHM :

1.Start the program.
   
2.Import the Scanner class to read input from the user.
  
3.Define a class named Demo.
 
5.Inside the class, define a method check(int num)

6.Calculates the square of the number.

7.Prints the squared result.

8.In the main() method:

9.Create a Scanner object to take input.

10.Read an integer input and store it in the variable num.

11.Create an object s of the Demo class.

12.Call the check(num) method using the object s.

13.End the program.




## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: kolluru pujitha
RegisterNumber:  212223240074
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Demo
{
public void check(int num)
{
    num=num*num;
    System.out.println(num);
}
public static void main(String[] args) 
    {
        Scanner in = new Scanner(System.in);
        int num=in.nextInt();
    Demo s=new Demo();
    s.check(num);   
    }
}


```




## OUTPUT:
<img width="351" height="161" alt="Screenshot 2026-03-27 234816" src="https://github.com/user-attachments/assets/030d958d-aded-4af4-b950-4be921afee7b" />




## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

