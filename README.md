# avg
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        float n;
        float sum=0.0f;
        for (int i = 1; i <= 10; i++)
        {
            System.out.println("enter #" +i+" :");
            Scanner k=new Scanner(System.in);
            n=k.nextInt();
            sum+=n;
        }
        System.out.println("Avg = " + sum/10);
    }
}
