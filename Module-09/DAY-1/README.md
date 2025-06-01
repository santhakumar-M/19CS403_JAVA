# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To create a Java Program to store a String Value in a file "testout.txt" using Data Output Stream.

## ALGORITHM :
1.  The program creates testout.txt and initializes FileOutputStream and DataOutputStream. It prompts the user to enter a string, writes it to testout.txt using writeUTF(), and then closes the streams.
2.	It reopens testout.txt with FileInputStream and DataInputStream, reads the stored string using readUTF(), displays it, and then closes the streams.
3.	It deletes testout.txt.
4.	After deletion, it tries to read an integer from testout.txt, which causes an error because the file no longer exists.
5.	The program catches and displays an IOException message if any file-related error occurs, including the attempt to read after deletion.


## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: SANTHAKUMAR
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:


```
 FileInputStream input = new FileInputStream("OutputFile.txt");  
    DataInputStream di = new DataInputStream(input);  
   // int count = input.available();  
 boolean data =di.readBoolean();
   
      System.out.println(data);  
    input.close();
    di.close();

```




## OUTPUT:

![image](https://github.com/user-attachments/assets/8f782fe3-4f70-4efe-bd4f-c9ba850a234a)


## RESULT:
Thus the Java Program to store a String Value in a file "testout.txt" using DataOutputStream was executed and verified successfully.

