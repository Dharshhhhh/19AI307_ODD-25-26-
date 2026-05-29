# Ex. No:2(E) ACCESS MODIFIERS

## QUESTION:

<img width="1005" height="40" alt="image" src="https://github.com/user-attachments/assets/ad9f1d65-74a3-406a-9823-dfa89e1a81d6" />
<img width="246" height="136" alt="image" src="https://github.com/user-attachments/assets/115e26a2-e648-4d26-8505-29e03948d38e" />


## AIM:

To write a Java program to Create a class College with a final variable universityName = "Saveetha University" and  Create objects and print the name.

## ALGORITHM :
1. Start the program and define a College class with a final variable universityName.

2. Assign the value "Saveetha University" to the final variable.

3. In the main method, create an object c1 of the College class.

4. Access the universityName using the object.

5. Display the university name and stop the program.





## PROGRAM:
 ```
Program to implement a Access Modifiers using Java
Developed by: DHARSHINI R
RegisterNumber:  212224220023
```

## SOURCE CODE:

```java
import java.util.Scanner;
class College 
{
    final String universityName = "Saveetha University";
}

public class prog 
{
    public static void main(String[] args) 
    {
        College c1 = new College();
        System.out.println(c1.universityName);
    }
}
```





## OUTPUT:
<img width="507" height="136" alt="image" src="https://github.com/user-attachments/assets/53c633c4-01ea-48da-8a8c-bcae41383609" />


## RESULT:

Thus, the Java program to Create a class College with a final variable universityName = "Saveetha University" and  Create objects and print the name has been executed successfully.
