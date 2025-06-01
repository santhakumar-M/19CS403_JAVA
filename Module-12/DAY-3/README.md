# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )
## ALGORITHM :

1.	Start the Program
2.	In `main`:
-	a) Create a `Scanner` object to read input.
-	b) Read an integer `n1` (the size of the first vector).
-	c) Initialize `Vector<String> vector1`.
-	d) Use a `for` loop to read `n1` strings and add each to `vector1`.
3.	Repeat similar steps for a second vector:
a)	Read an integer `n2` (size of the second vector).
b)	Initialize `Vector<String> vector2`.
c)	Use a `for` loop to read `n2` strings and add each to `vector2`.
4.	Use `equals()` to compare `vector1` and `vector2` and print whether they are equal.
5.	End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Demo{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        Vector<String> vec= new Vector<String>();
        for (int i=0;i<n;i++)
        {
            vec.add(sc.next());
            vec.add(sc.next());
        }
        System.out.println("The vector is: "+vec);
        Enumeration enu = vec.elements();
        System.out.println("The enumeration of values are:");
        while (enu.hasMoreElements())
        {
            System.out.println(enu.nextElement());
        }
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/32bf8332-f5ad-48f0-bb4f-45660e6b5204)


## RESULT:

Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method ) was executed successfully.








