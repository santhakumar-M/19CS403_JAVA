# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection.


## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: SANTHAKUMAR M
RegisterNumber:  212222040149
*/
```

## Sourcecode.java:
```
import java.util.*;
class Student
{
	String name;
	float percentage;
	Student(String name, float percentage)
	{
		this.name = name;
		this.percentage = percentage;
	}
}
class PercentageComparator implements Comparator<Student> {
	public int compare(Student stud1, Student stud2)
	{
		if(stud1.percentage < stud2.percentage)
			return 1;
		return -1;
	}
}
public class Main {
	public static void main(String args[])
	{
	
		ArrayList<Student> studList = new ArrayList<Student>();
		Scanner sc=new Scanner(System.in);
		int size=sc.nextInt();
		for(int i=0;i<size;i++)
		{
		    studList.add(new Student(sc.next(), sc.nextInt()));
		}
		
		Comparator<Student> com = new PercentageComparator();
		
		Collections.sort(studList, com);
		
		System.out.println("Avg % --> Name");
		System.out.println("---------------------");
		for(Student stud:studList) 
		{
			System.out.println(stud.percentage + " --> " + stud.name);
		}		
	}	
}
```






## OUTPUT:

![Image](https://github.com/user-attachments/assets/a05b5984-5ade-4d65-b0e8-2dbb97fe659c)

## RESULT:
Thus the java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection was executed successfully




