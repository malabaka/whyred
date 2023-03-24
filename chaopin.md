import java.util.Scanner;

public class QuadraticFunction {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the value of a: ");
        double a = scanner.nextDouble();

        System.out.print("Enter the value of b: ");
        double b = scanner.nextDouble();

        System.out.print("Enter the value of c: ");
        double c = scanner.nextDouble();

        System.out.print("Enter the value of d: ");
        double d = scanner.nextDouble();

        System.out.print("Enter the value of e: ");
        double e = scanner.nextDouble();

        System.out.print("Enter the value of x: ");
        double x = scanner.nextDouble();

        double result = a * Math.pow(x, 4) + b * Math.pow(x, 3) + c * Math.pow(x, 2) + d * x + e;

        System.out.println("The value of the quadratic function for x = " + x + " is " + result);
    }
}
# whyred
