# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Parent have method " display" to display "This is Parent Class". Child1 have method "print" to display "This is Child1 Class" Child1 have method "print" to display "Child2 Class". In Main create object for both child1 and child2 and access its member function.


## ALGORITHM :
1.  Start the Program
2.	Define class `Parent`:
-	a) Method `show()` to print "This is Parent Class"
3.	Define class `Child1` that extends `Parent`:
-	a) Method `print()` to print "This is Child1 Class"
4.	Define class `Child2` that extends `Parent`:
-	a) Method `display()` to print "This is Child2 Class"
5.	In `Main` class `main` method:
-	a) Create `Child1` object `child` and call `show()` and `print()` on it
-	b) Create `Child2` object `chi` and call `show()` and `display()` on it
6.	End




## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: SANTHAKUMAR M
RegisterNumber:  212222040149
*/
```

## Sourcecode.java:

```
class Operation {
   
    public int add(int a, int b) {
        return a + b;
    }

   
    public int subtract(int a, int b) {
        return a - b;
    }
}


class Addition extends Operation {
   
    public int addValues(int a, int b) {
        return add(a, b); 
    }
}


class Subtraction extends Operation {
    
    public int subtractValues(int a, int b) {
        return subtract(a, b); 
    }
}


public class Main {
    public static void main(String[] args) {
        
        Addition addObj = new Addition();
        Subtraction subObj = new Subtraction();

        
        int value1 = 10;
        int value2 = 5;

        
        int additionResult = addObj.addValues(value1, value2);
        int subtractionResult = subObj.subtractValues(value1, value2);

        
        System.out.println("Addition of 2 values " + additionResult);
        System.out.println("Subtraction of 2 values " + subtractionResult);
    }
}
```





## OUTPUT:
![Image](https://github.com/user-attachments/assets/9e817057-7f45-43fc-83da-7820daa06699)


## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






