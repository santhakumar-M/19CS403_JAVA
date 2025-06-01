# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End
## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:
```
class Progress_Report
{
    private String stuId;
    
    Progress_Report()
    {
        this.stuId = "12345";
    }
    
    class Exam
    {
        private float mark1;
        private float mark2;
        private float mark3;
        
        Exam()
        {
            this.mark1 = (float) 89;
            this.mark2 = (float) 78;
            this.mark3 = (float) 67;
        }
        public void display()
        {
            float sum = (mark1+mark2+mark3);
            System.out.print("Saveetha "+stuId);
        }
    }
}

public class Main
{
    public static void main(String[]args)
    {
        Progress_Report obj = new Progress_Report();
        Progress_Report.Exam obj1 = obj.new Exam();
        obj1.display();
    }
}
```
## OUTPUT:

![Image](https://github.com/user-attachments/assets/d6131ade-8282-4b13-9167-61c9baa4be93)

## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

