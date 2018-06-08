# nstars
package com.company;

import java.util.Scanner;

public class Nstars {
    public static void main(String[] args)
    {
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();
        int i;
        for(i=0;i<n;i++)
        {
            System.out.print("*");
        }
    }
}
