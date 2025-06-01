# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by:SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:

```
          FileReader fr=new FileReader("sample.txt");   
          BufferedReader br=new BufferedReader(fr);    
          Scanner sc=new Scanner(System.in);
int skch=sc.nextInt();
          br.skip(skch);
           char[] array = new char[36];
        System.out.println("Data after skipping "+skch+" characters:");
        br.read(array);
      System.out.println(array);
          
          
          br.close();    
          fr.close();
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/8abd5bf3-40ce-4989-b272-bc153d3ef420)


## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


