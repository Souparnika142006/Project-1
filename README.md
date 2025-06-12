#student info
import java.util.Scanner;

public class StudentInfo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("----- Student Information -----");

        System.out.print("Enter student name: ");
        String name = scanner.nextLine();

        System.out.print("Enter student age: ");
        int age = scanner.nextInt();

        System.out.print("Enter student marks: ");
        double marks = scanner.nextDouble();

        System.out.println("\n--- Student Details ---");
        System.out.println("Name  : " + name);
        System.out.println("Age   : " + age);
        System.out.println("Marks : " + marks);
    }
}# Project-1
This is a simple java console app for student info
# Project1 – Java Console App

This is a simple Java application to collect and print student info.

## How to Run

```bash
javac src/StudentInfo.java
java StudentInfo
