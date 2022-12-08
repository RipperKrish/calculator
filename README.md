# calculator
Basic Calculator
import java.util.Scanner;
class calculator {

    public static void main(String[] args) {
        int firstnumber;
        int secondnumber;
        int fundamentalmethod;
        try (Scanner myObj = new Scanner(System.in)) {
            System.out.println("please enter first number");
            firstnumber = Integer.parseInt(myObj.nextLine());
            System.out.println("please enter second number");
            secondnumber = Integer.parseInt(myObj.nextLine());
            System.out.println("please enter 1 for addition , 2 for subtraction , 3 for multiplication and  4 for division ");
            fundamentalmethod = Integer.parseInt(myObj.nextLine());
            int sum;
            if (fundamentalmethod == 1) {
                sum = firstnumber + secondnumber;
                System.out.println(sum);
            }
            int sub;
            if (fundamentalmethod == 2) {
                sub = firstnumber-secondnumber;
                System.out.println(sub);
                }

            }
                int multiply;
                if (fundamentalmethod == 3) {
                    multiply = firstnumber * secondnumber;
                    System.out.println(multiply);
                }
                int divide;
                if (fundamentalmethod == 4){
                    divide = firstnumber/secondnumber;
                    System.out.println(divide);
                }
        }
    }





