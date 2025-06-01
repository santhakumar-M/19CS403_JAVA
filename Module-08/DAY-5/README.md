# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java program that takes continuous input from the user using InputStreamReader and exits when the input ends with the symbol #. The input is taken inside a do-while loop.
## ALGORITHM :
1.	Start the program.
2.	Import java.io.*.
3.	Create an InputStreamReader and wrap it in a BufferedReader.
    	Use a do-while loop to:
    	Prompt and read input from the user.
    	Check if the input ends with #.
4.	If yes, break the loop.
    	Otherwise, print the input.
    	Close the input stream.
5.	End the program


## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by:SANTHAKUMAR M
RegisterNumber:  212222040149
*/
```

## Sourcecode.java:
```
try
{
    FileInputStream fin = new FileInputStream("sample.txt");
    System.out.println("Available bytes in the file: "+fin.available());
    Scanner sc = new Scanner(System.in);
    int s = sc.nextInt();
    fin.skip(s);
    System.out.println("Available bytes in the file: "+fin.available());
    
} 
catch (IOException e) 
{
    System.out.println("An error occurred.");
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/5fefcf9e-51e5-4982-9faa-c3b0a5ce1032)


## RESULT:
Thus, the java program uses InputStreamReader to read input and handles loop termination based on the presence of # at the end of the input string, as specified. 

