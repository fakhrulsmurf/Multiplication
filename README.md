# Multiplication

import java.util.Scanner;
 
class Multiplication
{
   public static void main(String args[])
   {
      int a,b,c;
      System.out.println("Enter two integers ");
      Scanner in = new Scanner(System.in);
      a=in.nextInt();
      b=in.nextInt();
      c=a*b;
      System.out.println("Multiplication of entered integers = ");
      System.out.print(c);
   }
}
