package scenaio1;

import java.util.Scanner;
 
 public class Scenaio1 {
     
     
     public static void main(String[] args) {
     
     Scanner sc = new Scanner(System.in);
     
     System.out.println("Enter your 1st Number");
     int a = sc.nextInt();
     System.out.println("Enter your 2nd Number");
     int b = sc.nextInt();
     
     int c;
     c = a+b;
     
     System.out.println("Your 1st number is " +a);
     System.out.println("Enter your 2nd number is " +b);
     System.out.println("Total amount is" +c);
     
 }
 }
