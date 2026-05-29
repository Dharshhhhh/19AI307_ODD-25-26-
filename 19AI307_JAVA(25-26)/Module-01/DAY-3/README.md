# Ex. No:1(C) LOOPING STATEMENT

## QUESTION:
<img width="1261" height="544" alt="image" src="https://github.com/user-attachments/assets/b59307b7-9120-4180-b5a2-8df7baea103c" />

## AIM:

To write a Java program that reads the number of terms from the user and displays the Fibonacci series using a for loop.      

## ALGORITHM :
1. Start the program and read the number of terms n from the user.

2. Initialize the first two Fibonacci numbers a = 0 and b = 1.

3. Display the first two terms 0 and 1.

4. Use a for loop from 3 to n to calculate the next term c = a + b and print it.

5. Update a = b and b = c in each iteration and stop the program after printing all terms.





## PROGRAM:
 ```
Program to implement a Looping Statement using Java
Developed by: DHARSHINI R
RegisterNumber: 212224220023
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int a=0,b=1,c;
        System.out.print("Fibonacci Series: ");
        if (n == 1) {
            System.out.print(a + " " + b);
            return;
        }
        System.out.print(a + " " + b + " ");
        for (int i=3;i<=n;i++)
        {
            c=a+b;
            System.out.print(c+" ");
            
            a=b;
            b=c;
            
        }
    }
}
```





## OUTPUT:
<img width="1022" height="284" alt="image" src="https://github.com/user-attachments/assets/cde209bd-d4c7-4a89-9c09-506f0b133b65" />


## RESULT:

Thus, the Java program that reads the number of terms from the user and displays the Fibonacci series using a for loop has been executed successfully.
