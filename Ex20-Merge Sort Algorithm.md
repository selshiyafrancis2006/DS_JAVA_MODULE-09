# Ex15 Value Existence Check in a TreeMap

## DATE:
11.11.2025  

## AIM:
To write a Java program that checks whether a given value exists in a TreeMap.

## Algorithm
1. Start the program.  
2. Create a `TreeMap` and insert key–value pairs.  
3. Use the `containsValue()` method to check if a specific value exists in the map.  
4. Display whether the value is found or not.  
5. Stop the program.  

## Program:
```java
/*
Program to check whether a given value exists in a TreeMap.
Developed by: Selshiya F
RegisterNumber: 212224060241
*/
import java.util.*;

public class TreeMapValueCheck {
    public static void main(String[] args) {
        TreeMap<Integer, String> map = new TreeMap<>();
        map.put(1, "Apple");
        map.put(2, "Banana");
        map.put(3, "Cherry");
        map.put(4, "Mango");

        System.out.println("TreeMap: " + map);
        String valueToCheck = "Banana";

        if (map.containsValue(valueToCheck))
            System.out.println("The value '" + valueToCheck + "' exists in the TreeMap.");
        else
            System.out.println("The value '" + valueToCheck + "' does not exist in the TreeMap.");
    }
}
```

## OUIPUT
<img width="940" height="83" alt="image" src="https://github.com/user-attachments/assets/e585fc8c-6505-4803-8863-ecefe234ea15" />

## RESULT
Thus, the program successfully checks whether a specified value exists in a TreeMap using the containsValue() method.
