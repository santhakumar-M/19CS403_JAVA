# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'roll_no' and initialize it with the value "5"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'roll_no' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Santhakumar M
RegisterNumber:  212222040149
*/

```

## Sourcecode.java:
```
class Student
{
    String name;
    int roll_no;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();
         obj.name="John";
        obj.roll_no=5;
      System.out.println(obj.name+" "+obj.roll_no);
    }    
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/5b82f119-ff7b-4141-8447-935d4fb3e426)


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'roll_no' was created successfully.
