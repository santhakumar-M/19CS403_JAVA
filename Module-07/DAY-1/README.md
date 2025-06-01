# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `Example1`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `a` and `b` from user input
-	b) Calculate `res = a / b` and print "Result: " followed by `res`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End







## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: SANTHAKUMAR M
RegisterNumber:  212222040149
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

![Image](https://github.com/user-attachments/assets/3d5e4e80-85d4-43cf-970b-668e4a09adf3)

## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

