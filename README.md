# Factorial-
import java.util.Scanner;

Public class Factorial {

        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a number:");
        int n= sc.nextInt();
        int fact = 1;
        for(int i=1;i<=n;i++)
        {
            fact*=i;
        }
            System.out.println(" The factorial of " + n + " is " + fact);
         }
}

OUTPUT:

Enter a number:
5
The factorial of 5 is 120
