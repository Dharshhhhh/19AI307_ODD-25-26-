# Ex. No:5(D) THREAD PRIORITY

## QUESTION:
<img width="919" height="343" alt="image" src="https://github.com/user-attachments/assets/d208751b-6c2f-4f7d-b892-715d9bbd056c" />


## AIM:

To Create a program that reads a thread name and a priority (1–10), sets that priority to a new thread, prints both values.



## ALGORITHM :
1. Start the program and create a Scanner object to read input from the user.

2. Read the thread name as a string and read the priority value as an integer from the user.

3. Create a new Thread object using the Thread class.

4. Set the thread name and priority using setName() and setPriority() methods.

5. Display the thread details by printing the thread name and its priority using getName() and getPriority().





## PROGRAM:
 ```
Program to implement a Thread Priority Concept using Java
Developed by: DHARSHINI R
RegisterNumber:  212224220023
```

## SOURCE CODE:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();
        int priority = sc.nextInt();

        Thread t = new Thread();
        t.setName(name);
        t.setPriority(priority);

        System.out.println("Thread " + t.getName() + " priority is " + t.getPriority());

        sc.close();
    }
}
```





## OUTPUT:

<img width="715" height="267" alt="image" src="https://github.com/user-attachments/assets/ddd171e8-8cee-4f43-8799-79bda4fa252e" />


## RESULT:

Thus, the java program to Create a program that reads a thread name and a priority (1–10), sets that priority to a new thread, prints both values.
