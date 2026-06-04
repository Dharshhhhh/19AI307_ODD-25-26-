# Ex. No:4(D) DESIGN PATTERN  ---- BEHAVIOUR PATTERN

## QUESTION:

# Ex. No:4(A) EXCEPTION HANDLING

## QUESTION:
<img width="1095" height="323" alt="image" src="https://github.com/user-attachments/assets/9879dee6-8a31-4e90-a29e-fab4700c9fe6" />


## AIM:

To identify and handle the NullPointerException that occurs when attempting to get the length of a null string, and ensure the program handles such situations gracefully.

## ALGORITHM :
1. Start the program.

2. Read a string input from the user using Scanner.

3. Check if the input equals "null" and assign the variable to null.

4. Try to find the length of the string using length() inside a try block.

5. If a NullPointerException occurs, catch it and print "Null string encountered", then end the program.




## PROGRAM:
 ```
Program to implement a Exception Handling using Java
Developed by: DHARSHINI R
RegisterNumber:  212224220023
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class main
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        String a = sc.nextLine();
        try
        {
            if (a.equals("null"))
            {
                a=null;
            }
            int len = a.length();
            System.out.println("Length: "+len);
        }
        catch (Exception e)
        {
            System.out.println("Null string encountered");
        }
    }
}
```





## OUTPUT:
<img width="691" height="658" alt="image" src="https://github.com/user-attachments/assets/a7be33b8-4d22-416d-9c78-90c427e30c49" />


## RESULT:

Thus, the java program to identify and handle the NullPointerException that occurs when attempting to get the length of a null string, and ensure the program handles such situations gracefully has been executed successfully.


