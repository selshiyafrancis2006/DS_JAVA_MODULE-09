# Ex12 Add Elements from an Array into a TreeSet

## DATE:
11.11.2025  

## AIM:
To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.

## Algorithm
1. Start the program.  
2. Initialize an array with integer elements.  
3. Create an empty `TreeSet`.  
4. Add all elements from the array into the `TreeSet`.  
5. Display the elements of the `TreeSet` (which are automatically sorted).  
6. Stop the program.  

## Program:
```java
/*
Program that adds elements from an array into a TreeSet and displays the elements in sorted order.
Developed by: Selshiya F
RegisterNumber: 212224060241
*/
import java.util.*;

public class ArrayToTreeSet {
    public static void main(String[] args) {
        Integer[] arr = {50, 20, 40, 10, 30};

        TreeSet<Integer> set = new TreeSet<>(Arrays.asList(arr));

        System.out.println("Array elements: " + Arrays.toString(arr));
        System.out.println("TreeSet elements (sorted): " + set);
    }
}

```
## OUTPUT 
<img width="925" height="78" alt="image" src="https://github.com/user-attachments/assets/22d8f7fe-02ed-49a6-8a2f-9e819ed1eaaf" />

## RESULT
The program successfully adds elements from an array into a TreeSet and displays them in sorted order.
