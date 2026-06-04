# Ex. No:4(A) EXCEPTION HANDLING

## QUESTION:
<img width="1253" height="70" alt="image" src="https://github.com/user-attachments/assets/dc8b59ed-1b7e-4101-b8db-8ed2693d6e5f" />


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
<img width="763" height="238" alt="image" src="https://github.com/user-attachments/assets/364a3711-c6c1-4e1a-a753-cdece7ae06ca" />


## RESULT:

Thus, the java program to identify and handle the NullPointerException that occurs when attempting to get the length of a null string, and ensure the program handles such situations gracefully has been executed successfully.
