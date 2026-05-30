# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
Start

Define class Subject:

Declare four String variables: subject1, subject2, subject3, subject4.

Create a method dispSub(String subject1, String subject2, String subject3, String subject4):

Print the four subjects separated by spaces.

Define class Student:

Declare an int variable Stu_Id.

Create an object obj of class Subject.

Create a method disp(int id):

Print the student ID.

Call dispSub method of Subject object obj, passing "B.Tech", "IT", "Third", "year".

Define class Main:

In the main method:

Create an object of Student class.

Call the disp method on the Student object, passing 101 as the student ID.








## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: kolluru pujitha
RegisterNumber:  212223240074
*/
```

## Sourcecode.java:
```

class Subject
{
    
    String subject1,subject2,subject3,subject4;
      
    void dispSub(String subject1,String subject2,String subject3,String subject4)
    {
        System.out.println(subject1+" "+subject2+" "+subject3+" "+subject4);
    }
}
class Student
{
    int Stu_Id;
    Subject obj = new Subject();
    
    
    void disp(int id)
    {
        System.out.println(id);
        obj.dispSub("B.Tech","IT","Third","year");
    }
}

public class Main
{
    public static void main(String[] args)
    {
        Student obj = new Student();
        obj.disp(101);
        
    }
}
```






## OUTPUT:
```
Input      Expected                 Got
---        101                      101
           B.Tech IT Third year     B.Tech IT Third year
```


## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

