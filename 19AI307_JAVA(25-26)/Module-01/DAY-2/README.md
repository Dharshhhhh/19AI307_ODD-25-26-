# Ex. No:1(B) CONDITIONAL STATEMENT

## QUESTION:
<img width="672" height="368" alt="image" src="https://github.com/user-attachments/assets/68f62b95-1aa1-4bdc-bc89-bc49802a5d10" />


## AIM:

To Write a Java program to simulate this elevator logic for a given floor number.



## ALGORITHM :
1. Start the program.

2. Read an integer value a from the user.

3. Check if a is divisible by both 3 and 5; if true, print "Skipped".

4. Otherwise check if a is divisible by 3 print "Beware!", else if divisible by 5 print "Blessings!".

5. If none of the above conditions are satisfied, print "Floor " + a and stop the program.





## PROGRAM:
 ```
Program to implement a conditional statement using Java
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
        int a = sc.nextInt();
        if ((a%3==0) && (a%5==0))
        {
            System.out.println("Skipped");
        }
        else if(a%3==0)
        {
            System.out.println("Beware!");
        }
        else if(a%5==0)
        {
            System.out.println("Blessings!");
        }
        else
        {
            System.out.println("Floor "+a);
        }
    }
}
```





## OUTPUT:
<img width="574" height="276" alt="image" src="https://github.com/user-attachments/assets/b06150b2-2ba1-455a-aba2-474dbb0fb5dc" />


## RESULT:

Thus, thr Java program to simulate this elevator logic for a given floor number has been executed Successfully.
