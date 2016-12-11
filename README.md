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

03. Even or odd

import java.util.Scanner;

public class ex03_Even_Or_Odd {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);

        int num = Integer.parseInt(console.nextLine());
        if (num % 2 == 0){
            System.out.println("Even");
        } else {
            System.out.println("Odd");
        }
    }
}

===========================================