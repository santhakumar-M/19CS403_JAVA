# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by:SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:
```
{
package com.example.app;

import com.example.constants.Constants;

public class MyApp {
    public static void main(String[] args) {
        int sumValue = Constants.SUM;
        System.out.println("The value of SUM is: " + sumValue);
    }
}
```
## OUTPUT:

![Image](https://github.com/user-attachments/assets/c967fc40-581f-47ef-b84b-c814b9fb6871)

## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

