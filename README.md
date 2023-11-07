# Ex-6 Create a method to calculate power of a number raised to other
# program
```
public class PowerCalculator {
    public static void main(String[] args) {
        double base = 2.0;
        int exponent = 3;
        double result = calculatePower(base, exponent);
        System.out.println(base + " raised to the power of " + exponent + " is " + result);
    }
    public static double calculatePower(double base, int exponent) {
        double result = 1.0;

        if (exponent >= 0) {
            for (int i = 1; i <= exponent; i++) {result *= base;}
        } else {for (int i = 1; i <= -exponent; i++) {result /= base;}}
        return result;
    }
}

```
# output
![image](https://github.com/Rohith-AIDS/calculation/assets/94980736/f62ba36f-325a-42de-af21-b5038a350f03)

