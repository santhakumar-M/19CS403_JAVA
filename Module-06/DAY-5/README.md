# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces to read student details and marks, calculate the average, and display the mark sheet.

## ALGORITHM :

1.	Start the program.
2.	Create interface Student:
a.	Declare methods to read name and rollno.
3.	Create interface Studentdet:
a.	Declare a method to read marks of 6 subjects and calculate the average.
b.	Create a class Studentdetails that implements both interfaces:
c.	Define variables for name, roll number, marks array, and average.
4.	Implement all methods from the interfaces.
a.	Create a display() method to show student details and average.
5.	In main() method:
a.	Create an object of Studentdetails.
b.	Call the methods to get input and display results.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:

```
class Student
{
    double mark = 5;
    void displayMarks()
    {
        System.out.println("Student's Assessment Marks : "+mark);
    }
}
class SportsStudent extends Student
{
    double inc = 5.0;
    void incrementMark()
    {
       System.out.println("Student's Assessment Marks : "+(mark+inc));
    }
}
class Extra_Curriculum extends Student
{
    double inc = 4.0;
    void incrementMark()
    {
        System.out.println("Student's Assessment Marks : "+(mark+inc));
    }
}
public class Main
{
    public static void main(String[] args)
    {
        SportsStudent emp1 = new SportsStudent();
        Extra_Curriculum emp2 = new Extra_Curriculum();
        System.out.println("Assessment Mark of the Sports Student before  before incrementing:");
        emp1.displayMarks();
        System.out.println("Assessment Mark of the Extra -Curriculum Acitvity Student before  before incrementing:");
        emp2.displayMarks();
        System.out.println("Assessment Mark of the Sports Student after  before incrementing:");
        emp1.incrementMark();
        System.out.println("Assessment Mark of the Extra -Curriculum Acitvity Student after  before incrementing:");
        emp2.incrementMark();
    }
}
```





## OUTPUT:

![Image](https://github.com/user-attachments/assets/47830484-c9ec-4d81-90d9-25b4ba31733e)

## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces and successfully displays the mark sheet of a student by collecting personal and academic data. 
