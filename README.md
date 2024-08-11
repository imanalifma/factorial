// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.Scanner;
 class HelloWorld {
     public static void main(String[]args){
         System.out.println("Enter a number:");
         Scanner scanner = new Scanner(System.in);
         int n = scanner.nextInt();
         
       
         System.out.println(factorial(n));
     }
     
     public static int factorial(int num){
       for(int i=0;i<=3;i++){
          num = num+=i; 
       }
       return num; 
     }
 }
 
