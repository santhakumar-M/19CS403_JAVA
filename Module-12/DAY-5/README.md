# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: SANTHAKUMAR M
RegisterNumber: 212222040149
*/
```

## Sourcecode.java:

```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	   Iterator iterator = pQueue.iterator();
	   System.out.println("Iterate the elements from the queue using while loop:");
  
        while (iterator.hasNext()) {
            System.out.print(iterator.next() + " ");
        }
		
	}
}
```





## OUTPUT:

![Image](https://github.com/user-attachments/assets/138afb45-6940-4194-827c-1c35781309f0)


## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


