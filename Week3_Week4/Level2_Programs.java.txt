import java.util.Scanner;

public class Level2_Programs {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        // Program 1: Odd Even numbers
        System.out.print("Enter a number: ");
        int number = input.nextInt();

        for (int i = 1; i <= number; i++) {
            if (i % 2 == 0)
                System.out.println(i + " Even");
            else
                System.out.println(i + " Odd");
        }


        // Program 2: Employee Bonus
        System.out.print("Enter salary: ");
        double salary = input.nextDouble();

        System.out.print("Enter years of service: ");
        int years = input.nextInt();

        if (years > 5)
            System.out.println("Bonus = " + salary * 0.05);
        else
            System.out.println("No Bonus");


        // Program 3: Multiplication table
        System.out.print("Enter number for table: ");
        int num = input.nextInt();

        for (int i = 6; i <= 9; i++) {
            System.out.println(num + " * " + i + " = " + (num * i));
        }

        input.close();
    }
}