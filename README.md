# java-program-to-print-the-Arithmetic-operations

## Program
```
import java.util.Scanner;

public class main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the first number: ");
        double num1 = scanner.nextDouble();

        System.out.print("Enter the second number: ");
        double num2 = scanner.nextDouble();

        double sum = num1 + num2;
        double difference = num1 - num2;
        double product = num1 * num2;

        double quotient = num2 != 0 ? num1 / num2 : Double.NaN;

        System.out.println("Sum: " + sum);
        System.out.println("Difference: " + difference);
        System.out.println("Product: " + product);
        System.out.println("Quotient: " + (Double.isNaN(quotient) ? "Cannot divide by zero" : quotient));

        scanner.close();
    }
}

```

## Output

![Screenshot (65)](https://github.com/21002624/java-program-to-print-the-Arithmetic-operations/assets/113762183/9099c207-f36b-4a44-a799-f3f8f197be2a)


