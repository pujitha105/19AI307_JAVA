# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

1.Start

2.Define class Laptop:

Declare a String variable brand.

Declare a double variable price.

Create a constructor Laptop():

Set brand to "Apple".

Set price to 42500.75.

3.Define a method getBrand():

Return the value of brand.

Define a method getPrice():

Return the value of price.

4.Define class Sample:

In the main method:

 Create an object myLaptop of class Laptop.
 
 Call getBrand() method using myLaptop and store the result in laptopBrand.
 
 Print laptopBrand.
 
 Call getPrice() method using myLaptop and store the result in laptopPrice.
 
 Print laptopPrice.
5.End

## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: kolluru pujitha
RegisterNumber:  212223240074
*/
```

## Sourcecode.java:
```
class Laptop {
    String brand;
    double price;
    public Laptop() {
        this.brand = "Apple";
        this.price = 42500.75;
    }

    public String getBrand() {
        return brand;
    }

    public double getPrice() {
        return price;
    }
}
public class Sample {
    public static void main(String[] args) {
        Laptop myLaptop = new Laptop();
        String laptopBrand = myLaptop.getBrand();
        System.out.println(laptopBrand);
        double laptopPrice = myLaptop.getPrice();
        System.out.println(laptopPrice);
    }
}
```







## OUTPUT:
<img width="368" height="173" alt="image" src="https://github.com/user-attachments/assets/7eb09563-30a6-446b-9597-4eb5b10134a2" />



## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


