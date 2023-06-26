# Sum-of-digits


Problem: Sum of the digits in a given number

import java.util.*;


class SumofDigits{
    static int sd(int n) {
        if(n==0){
            return 0;
        }
        
        return sd(n/10)+n%10;

    }
    public static void main(String... args){
        System.out.println("Enter the number: ");
        Scanner f=new Scanner(System.in);
        int n=f.nextInt();
        System.out.println("The sum of the digits in the given number : "+ sd(n));


    }
}






/*
Enter the number:
222
The sum of the digits in the given number : 6
 */


