# JAVA
package com.company.java.array;
import java.util.Scanner;

public class rating{
     public static void main(String[] args) {
     Scanner sc = new Scanner(System.in);
     int t = sc.nextInt();
     
     while(t != 0){
     int r = sc.nextInt();
     if(2000<=r){
     System.out.println("1");
     }
     else if(r<1600){
     System.out.println("3");
     }
     else{
     System. out.println("2");
     }
     t--;
     }
    }
   }
