# Ngoding100DaysH_20
package ngoding100daysh_20;

import java.util.Scanner;

public class Ngoding100daysH_20 {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("masukan gaji : ");
        int a = input.nextInt();
        double b = 0.05;
        double f = 0.1;
        if (a >= 5000000) {
            double c = a - (a * f);
            System.out.println("pajak 10%");
            System.out.println("gaji" + c);
        } else if (a >= 3000000 && a <= 5000000) {
            double c = a - (a * b);
            System.out.println("pajak 5%");
            System.out.println("gaji" + c);
        } else {
            System.out.println("tidak memiliki pajak");
        }
    }
}
