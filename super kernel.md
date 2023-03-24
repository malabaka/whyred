import java.util.Scanner;

public class NBAAnalysis {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the name of the home team: ");
        String homeTeam = scanner.nextLine();

        System.out.print("Enter the name of the away team: ");
        String awayTeam = scanner.nextLine();

        System.out.print("Enter the score of the home team: ");
        int homeScore = scanner.nextInt();

        System.out.print("Enter the score of the away team: ");
        int awayScore = scanner.nextInt();

        System.out.println("NBA Game Result Analysis:");
        System.out.println(homeTeam + " " + homeScore + " - " + awayTeam + " " + awayScore);

        if (homeScore > awayScore) {
            System.out.println(homeTeam + " wins!");
        } else if (homeScore < awayScore) {
            System.out.println(awayTeam + " wins!");
        } else {
            System.out.println("It's a tie!");
        }
    }
}
以下是Java代码，用于计算三元二次函数的值：

Copy
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

        System.out.print("Enter the value of x: ");
        double x = scanner.nextDouble();

        double result = a * Math.pow(x, 2) + b * x + c;

        System.out.println("The value of the quadratic function for x = " + x + " is " + result);
    }
}# whyred
name
