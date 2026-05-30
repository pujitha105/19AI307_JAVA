# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1. Start

2.  Import the Scanner class for input.

3. Define class Person:

   Declare a private int variable age.
   
   Create a method setAge(int age):
   
   Assign the input parameter age to the instance variable age.
   
   Create a method getAge():
   
   Return the value of age.

4. Define class Main:

   In the main method:
   
   Create a Scanner object scanner to read user input.
   
   Create an object p of class Person.
   
   Read an integer from the user and store it in inputAge.
   
   Call p.setAge(inputAge) to set the age in the Person object.
   
   Print "My age is " followed by the value returned by p.getAge().
   
   Close the scanner.

5. End





## PROGRAM:
## Sourcecode.java:

```
import java.util.Scanner;

class Person {
    private int age;

    public void setAge(int age) {
        this.age = age;
    }

    public int getAge() {
        return age;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Person p = new Person();

        int inputAge = scanner.nextInt();
        p.setAge(inputAge);

        System.out.println("My age is " + p.getAge());
        scanner.close();
    }
}

```







## OUTPUT:

<img width="477" height="254" alt="image" src="https://github.com/user-attachments/assets/185bbe32-f87f-4c5d-a631-0c9b01155788" />


## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
