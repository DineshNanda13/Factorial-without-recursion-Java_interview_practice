# Factorial-without-recursion-Java_interview_practice
Java program to find a factorial of a number
package factorial;

import java.util.Scanner;

/**
 *
 * @author Dinesh Nanda
 */

public class Factorial {

    public static void main(String[] args) {

        Scanner s = new Scanner(System.in);
        System.out.println("Enter a number");
        int number = s.nextInt();

        int fact = 1;

        for (int i = 1; i <= number; i++) {
            fact = fact * i;
        }
        System.out.println("The factorial is "+ fact);
    }
}
