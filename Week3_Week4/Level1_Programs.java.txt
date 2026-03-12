import java.util.Scanner;

public class Level1_Programs {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        // Program 1: Check divisible by 5
        System.out.print("Enter a number: ");
        int number = input.nextInt();

        if (number % 5 == 0)
            System.out.println("Number is divisible by 5");
        else
            System.out.println("Number is not divisible by 5");


        // Program 2: Check smallest number
        System.out.print("Enter three numbers: ");
        int a = input.nextInt();
        int b = input.nextInt();
        int c = input.nextInt();

        if (a < b && a < c)
            System.out.println("First number is smallest");


        // Program 3: Check largest number
        if (a > b && a > c)
            System.out.println("First number is largest");
        else if (b > a && b > c)
            System.out.println("Second number is largest");
        else
            System.out.println("Third number is largest");


        // Program 4: Sum of natural numbers
        System.out.print("Enter a natural number: ");
        int n = input.nextInt();

        if (n > 0)
            System.out.println("Sum = " + (n * (n + 1) / 2));
        else
            System.out.println("Not a natural number");

        input.close();
    }
}