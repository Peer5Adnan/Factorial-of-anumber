# Factorial-of-anumber
public class Factorial {
    public static void main(String args[]) {
        System.out.println("welcome here now we will find factorial of any number");
        int num;
        num = 9;
        int fact = 1;
        if (num > 0) {
            for (int i = 1; i <= num; i++) {
                fact = fact * i;
            }
        }
        System.out.println("factoial of number is           " + fact);
    }
}

