# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Develop a Java program to create Thread using Thread class.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Create a `Scanner` instance for user input.
-	b) Override the `run` method:
-	i) Read a string from user input.
-	ii) Print "Thread Name:" followed by the input string.
4.	In the `main` method:
-	a) Create an instance of `Multi`.
-	b) Create a new `Thread` instance using the `Multi` object.
-	c) Start the thread with `t1.start()`.
5.	End





## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:

```
import java.util.*;
public class A implements Runnable
{
public void run()
{
  System.out.println(Thread.currentThread()); // This method is static.
}
public static void main(String[] args) 
{
 A a = new A();
 Scanner sc=new Scanner(System.in);
 String thname=sc.nextLine();
 Thread t = new Thread(a, thname);
 t.setPriority(2); // Setting the priority of thread.
 System.out.println("Priority of Thread: " +t.getPriority());
 System.out.println("Name of Thread: " +t.getName());
 t.start();
  }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/05043c7e-898b-4157-8cb7-090bf7643b1c)


## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.







