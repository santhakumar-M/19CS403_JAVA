# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To implement a Java Program to write a String in a file "testout.txt" using FileOutputStream

## ALGORITHM :
1.  Define the string "Welcome to Saveetha" and convert it to a byte array b using getBytes().
2.	Use Scanner to prompt the user for start (starting index) and length (number of bytes) to write from the string.
3.	Open testout.txt using FileOutputStream, and write the specified portion of b from the start index for length bytes, then close the output stream.
4.	Open testout.txt using FileInputStream, read its contents byte-by-byte, convert each byte to a character, and print it to display the file's content.
5.	Use file.delete() to delete testout.txt.
6.	Attempt to read the deleted file, which triggers a FileNotFoundException as the file no longer exists.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:
```

 byte[] array = new byte[39];
             FileInputStream input = new FileInputStream("sample.txt");
              System.out.println("Available bytes in the file: " +input.available());
              input.read(array);
              String data = new String(array);
              System.out.println("Data read from the file:" +data);
              input.close();
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/0ce05546-a859-4626-8896-29120f20ac6c)


## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

