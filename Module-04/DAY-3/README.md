# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
Step 1: Start

Step 2: Define a class Gadgets

a. Create a method display()

b. Inside display(), print "I am a Gadget"

Step 3: Define a class Parrot that extends Gadgets

a. Override the display() method

b. Inside the overridden display(), print "I am a Laptop"

c. Create a new method print()

d. Inside print(), use super.display() to call the parent class (Gadgets) version of display()

Step 4: Define the Main class with main() method

a. Create an object obj of class Parrot

b. Call obj.display() → Executes Parrot class's display() method

c. Call obj.print() → Executes Parrot class's print() method, which in turn calls Gadgets class's display() method using super

Step 5: End





## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: kolluru pujitha
RegisterNumber:  212223240074
*/
```

## Sourcecode.java:

```

class Gadgets {

  void display()
  {
      System.out.println("I am a Gadget");
  }
}

class Parrot extends Gadgets {

void display()
{
    System.out.println("I am a Laptop");
}
void print()
{
    super.display();
}
  
}

public class Main {
  public static void main(String[] args) {
      
      Parrot obj=new Parrot();
      obj.display();
      obj.print();
  }
}

```





## OUTPUT:


<img width="403" height="198" alt="image" src="https://github.com/user-attachments/assets/d21326dd-8d96-4a53-9104-9c1c916c562a" />

## RESULT:
Thus the java program for constructor chaining was executed successfully.




