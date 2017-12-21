/* https://www.hackerrank.com/challenges/java-datatypes/problem */

import java.util.*;
import java.io.*;

class Solution{
    public static void main(String []argh)
    {
        Scanner sc = new Scanner(System.in);
        int t=sc.nextInt();
        for(int i=0;i<t;i++)
        {
            try
            {
                long x=sc.nextLong();
                System.out.println(x+" can be fitted in:");
                
                /*A byte is an 8-bit signed integer.
                A short is a 16-bit signed integer.
                An int is a 32-bit signed integer.
                A long is a 64-bit signed integer.*/

                if(x>=-128 && x<=127)System.out.println("* byte");
                if(x>=-Math.pow(2,15) && x<=(Math.pow(2,15) -1))System.out.println("* short");
                if(x>=-Math.pow(2,31) && x<=(Math.pow(2,31)-1))System.out.println("* int");
                if(x>=-(Math.pow(2,63)) && x<=Math.pow(2,63)-1)System.out.println("* long");
             }
            catch(Exception e)
            {
                System.out.println(sc.next()+" can't be fitted anywhere.");
            }

        }
    }
}
