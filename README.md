# GuessStarter

import java.util.Random;
import java.util.Scanner;

/**
 * Starter code for the "Guess My Number" exercise.
 */
public class GuessStarter {

    public static void main(String[] args) {
        int x;  
        Scanner in = new Scanner(System.in);
        
        // input a random number
        System.out.print("pick a random number between 1-100.");
        x = in.nextInt();
        
        // pick a random number
        Random random = new Random();
        int number = random.nextInt(100) + 1;
        System.out.println("This is the number I was thinking: " + number);
        
        // The difference between the two numbers
        System.out.println("This is the difference between the two numbers: " + (x - number));
        
    }


}
