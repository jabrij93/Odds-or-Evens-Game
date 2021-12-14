import java.util.Random;
import java.util.Scanner;

public class OddsAndEvens_m2 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Let's play a game called \"Odds and Evens\"");
        System.out.println("What is your name? ");
        String name = input.next();
        System.out.println("Hi "+name+", which do you choose? (O)dds or (E)vens?");
        String name2 = input.next();

        if (name2.equals("O")) {
            System.out.println(name+" has picked "+name2+"! The computer will be evens.");
        } else if (name2.equals("E")) {
            System.out.println(name+" has picked "+name2+"! The computer will be odds.");
        }
        else {
            System.out.println("Please pick either odds or evens!");

            System.out.println("--------------------------------------------");
        }

        if(name2.equals("E")||name2.equals("O"))
        {
            System.out.println("-----------------------------------------------------------");
            System.out.println("How many \"fingers\" do you put out?");
            int userNumber = input.nextInt();

            Random rand = new Random();
            int computer = rand.nextInt(6);
            System.out.println("The computer plays number "+computer);
            System.out.println("-----------------------------------------------------------");
            int sum = computer + userNumber;
            System.out.println("The sum is "+ sum);

            boolean oddOrEven = sum % 2 == 0;

            if (oddOrEven) {
                System.out.println(sum+" is even..!");
                if (name2.equals("E")) {
                    System.out.println(name+" wins!");
                }
                else if (name2.equals("O")) {
                    System.out.println("The computer wins!");
                }
            }
            else {
                System.out.println(sum+" is odd..!");
                if (name2.equals("E")) {
                    System.out.println("The computer wins!");
                } if (name2.equals("O")) {
                    System.out.println(name+" wins!");
                }
            }
        }
        System.out.println("-----------------------------------------------------------");
    }
}
