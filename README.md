# Java-03


===========================================

01.Excellent result

import java.util.Scanner;

public class ex01_Excellent_Result {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double grade = Double.parseDouble(console.nextLine());
        if (grade >= 5.50){
            System.out.println("Excellent!");
        }
    }
}

===========================================

===========================================

02.Excellent or not

import java.util.Scanner;

public class ex02_Excellent_Or_Not {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        double grade = Double.parseDouble(console.nextLine());
        if (grade >= 5.50){
            System.out.println("Excellent!");
        } else {
            System.out.println("Not excellent.");
        }
    }
}

===========================================

===========================================