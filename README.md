# Do-while-loop
Do-While Loop

import java.util.Scanner;

public class DoWhileLoopExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num;
        do {
            System.out.print("Enter a positive number (or -1 to exit): ");
            num = sc.nextInt();
            if (num >= 0) {
                System.out.println("You entered: " + num);
            }
        } while (num != -1);
        System.out.println("Exited.");
    }
}

Output

Enter a positive number (or -1 to exit): 10  
You entered: 10  
Enter a positive number (or -1 to exit): -1  
Exited
