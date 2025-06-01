# Ex.No:7(E)  POLYMORPHISM

## AIM:
To implement method overloading in Java to calculate the sum of two and three numbers demonstrating compile-time polymorphism
## ALGORITHM :
1.	Start the program.
2.	Create a class named SumExample.
3.	Inside the class, define:
     a.	A method sum(int a, int b) to calculate the sum of two numbers.
     b.	An overloaded method sum(int a, int b, int c) to calculate the sum of three numbers.
4.	In the main() method:
      a.	Create an object of the SumExample class.
      b.	Call both versions of the sum() method with appropriate arguments.
      c.	Print the results.
5.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: SANTHAKUMAR M
RegisterNumber: 2122222040149
*/
```

## Sourcecode.java:


```
import java.util.*;

public class HelloWorld{

        void sum(int a,int b){
    System.out.println(a+b);
   }
  void sum(double a,double b){
    System.out.println(a+b);
  }

  public static void main(String []args)
    {
  HelloWorld obj=new HelloWorld();
  Scanner sc=new Scanner(System.in);
  int a=sc.nextInt();
  int b=sc.nextInt();
  double c=sc.nextDouble();
  double d=sc.nextDouble();
  obj.sum(a,b);
  obj.sum(c,d);
     }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/78160150-0273-4024-840d-ba812d8fec8e)


## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism by calculating the sum of two and three numbers using methods with the same name but different parameter lists..


