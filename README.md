# Multiplication

import java.util.Scanner;
 
class Multiplication
{
   public static void main(String args[])
   {
      int x, y, z;
      System.out.println("Enter two integers ");
      Scanner in = new Scanner(System.in);
      x = in.nextInt();
      y = in.nextInt();
      z = x + y;
      System.out.println("Multiplication of entered integers = "+z);
   }
}
