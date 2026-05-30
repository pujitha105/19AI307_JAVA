# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
Step 1: Start

Step 2: Import the required classes: import java.util.* for Scanner and StringTokenizer.

Step 3: Create the Main class.

Step 4: Inside the main method:

a. Create a Scanner object to read user input.

b. Read a full line of text input from the user using nextLine().

c. Create a StringTokenizer object with the input string as its argument.

d. Use countTokens() method to count the number of tokens (words separated by whitespace by default).

e. Print the total number of tokens.

Step 5: End


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: kolluru pujitha
RegisterNumber:  212223240074
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main
{
    public static void main(String[]args)
  {
        Scanner scan = new Scanner(System.in);
        String name = scan.nextLine();
        StringTokenizer st = new StringTokenizer(name);
        System.out.println("Total number of Tokens: "+st.countTokens());
   }
}


```





## OUTPUT:
<img width="846" height="322" alt="image" src="https://github.com/user-attachments/assets/d2459aaa-2316-4dca-8e47-eec4ba83f643" />



## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

