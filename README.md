
import java.util.Scanner;

public class HealthCheck {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("=== Student Health Check ===");

        System.out.print("Enter student name: ");
        String name = scanner.nextLine();

        System.out.print("Is the student wearing a mask? (yes/no): ");
        String mask = scanner.nextLine();

        System.out.print("Enter body temperature in Celsius: ");
        double temp = scanner.nextDouble();

        System.out.println("\n--- Health Check Result ---");
        if (mask.equalsIgnoreCase("yes") && temp <= 37.5) {
            System.out.println("Access granted to " + name + ".");
        } else {
            System.out.println("Access denied to " + name + ".");
        }
    }
}
# HealthMonitorJava

A simple Java console application that simulates student health checking, including:

- Mask-wearing status (yes/no)
- Body temperature check
- Access control decision

## 🚀 How to Run

Compile:
