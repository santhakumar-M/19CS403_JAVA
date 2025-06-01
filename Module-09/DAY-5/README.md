# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:


```
import java.io.StringWriter;
import java.util.*;
public class Main {
  public static void main(String[] args) {

    
     Scanner sc=new Scanner(System.in);
     String data = sc.nextLine();
   
    try {
      // Create a StringWriter with default string buffer capacity
      StringWriter output = new StringWriter();

      // Writes data to the string buffer
      output.write(data,2,4);

      // Prints the string writer
      System.out.println("Input String: " + data);
      System.out.println("Specified Location: " + output);

      output.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/91766141-89da-42ba-b0ae-8742d3aed008)



## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

