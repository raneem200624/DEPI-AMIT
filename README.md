


import java.util.Scanner;

public class Main {
    public static void main(String[] args){
       Scanner s=new Scanner(System.in);

       System.out.print("Enter first number: ");
       double x = s.nextDouble();          
       System.out.print("Enter second number: ");
       double y = s.nextDouble();         
       System.out.println("Sum: "+(x+y));          
       System.out.println("Difference: "+(x-y));  
       System.out.println("Product: "+(x*y));      
       System.out.println("Quotient: "+(x/y));
       
    }
}
