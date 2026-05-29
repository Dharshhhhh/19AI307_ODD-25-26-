# Ex. No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
<img width="788" height="210" alt="image" src="https://github.com/user-attachments/assets/68dcf625-5191-498d-a261-faa6b3faef0e" />

## AIM:

To write a Java program to calculate the power of a given number.



## ALGORITHM :
1. Start the program and create a Scanner object to read user input.

2. Read two double values a (base) and b (exponent) from the user.

3. Calculate the power using Math.pow(a, b).

4. Display the result in the format "a raised to the power of b is: result".

5. Stop the program.




## PROGRAM:
 ```
Program to implement a Strings and Math Function using Java
Developed by: DHARSHINI R
RegisterNumber:  212224220023
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        double a = sc.nextDouble();
        double b = sc.nextDouble();
        System.out.println(a+ " raised to the power of "+b+" is: "+Math.pow(a,b));
    }
}
```





## OUTPUT:
<img width="1143" height="286" alt="image" src="https://github.com/user-attachments/assets/3f145832-7f48-4627-a25f-c0d9851e5ca8" />

## RESULT:

Thus, the Java program to calculate the power of a given number has been executed successfully.
