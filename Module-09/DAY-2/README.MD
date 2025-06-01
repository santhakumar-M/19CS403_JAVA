# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :
1.	The user enters a string (data), followed by two integers (start and length) specifying the starting position and number of characters to write.
2.	The string data is converted to a byte array (array).
3.	Using ByteArrayOutputStream, it writes length bytes from array, starting at start.
4.	The written data is retrieved as a string (streamData) and displayed, showing the original input and the specific segment written to the stream.
5.	Any exceptions are caught and handled, displaying stack trace information if an error occurs.




## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:
```
import java.io.*;
import java.util.*;
public class Main {
    public static void main(String[] args) {

    
     Scanner sc=new Scanner(System.in);
     String data =sc.nextLine();
    try {
      // Creates an output stream
      ByteArrayOutputStream out = new ByteArrayOutputStream();
      byte[] array = data.getBytes();

      // Writes data to the output stream
      out.write(array,3,6);

      // Retrieves data from the output stream in string format
      String streamData = out.toString();
      System.out.println("Original data: " + data);
      System.out.println("Output stream: " + streamData);
      out.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```







## OUTPUT:

![Image](https://github.com/user-attachments/assets/6517094e-7b99-433f-988e-1340dd8ff7f2)

## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





