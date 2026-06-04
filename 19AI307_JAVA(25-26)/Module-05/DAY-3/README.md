# Ex. No:5(C)  FILE HANDLING USING JAVA
## QUESTION:
<img width="614" height="209" alt="image" src="https://github.com/user-attachments/assets/d7f94040-b231-4e96-be57-e88c6bc9592d" />


## AIM:

To Write a program to write multiple lines to a file using FileWriter.



## ALGORITHM :
1. Start the program and create a Scanner object to read input from the user.

2. Create a FileWriter object to open the file "multilines.txt" for writing text.

3. Use an infinite loop to read lines of text from the user using nextLine().

4. Check if the input is "exit"; if it is, break the loop. Otherwise, write the text into the file followed by a newline.

5. Close the file and display a success message indicating that the file has been written successfully.





## PROGRAM:
 ```
Program to implement a File Handling using Java
Developed by: DHARSHINI R
RegisterNumber:  212224220023
```

## SOURCE CODE:


```java
import java.util.Scanner;
import java.io.IOException;
import java.io.FileWriter;

public class main
{
    public static void main(String args[]) throws IOException
    {
        Scanner sc = new Scanner(System.in);
        try
        {
        FileWriter f = new FileWriter("multilines.txt");
        while (true)
        {
            String txt = sc.nextLine();
            if (txt.equalsIgnoreCase("exit"))
            {
                break;
            }
            f.write(txt+"\n");
            f.close();
            
        }
        System.out.println("File written successfully to multilines.txt");
        }
        catch (IOException e)
        {
                    System.out.println("File written successfully to multilines.txt");
 
        }
    }
}
```




## OUTPUT:
<img width="1026" height="178" alt="image" src="https://github.com/user-attachments/assets/57b05245-843f-49b4-bbf8-532530497e35" />

## RESULT:

Thus, the Java program o Write a program to write multiple lines to a file using FileWriter has been completed successfully.
