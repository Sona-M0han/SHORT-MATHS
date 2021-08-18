// Prints Prime Numbers upto an input value //

import java.util.Scanner;
public class Main
{
  public static void main(String[] args)
  {
       int count;
       System.out.println("PRIME NUMBERS");
       System.out.print("Enter a number:");
       Scanner scan = new Scanner(System.in);
       int num = scan.nextInt();
       scan.close();


       if (num<=1)
            System.out.println("There aren't any prime numbers till "+num);
       else
       {
            System.out.println("Prime numbers upto "+num+" are: ");
            int i=2;
         while (i <= num)
         {
              count = 0;
              for (int j = 2; j <= (i / 2); j++)
              {
                    if (i % j == 0)
                    {
                        count++;
                        break;
                    }
              }
              if (count == 0)
              System.out.println(i);
              i++;
         }
       }

   }
}
