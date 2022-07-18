# In-this-problem-you-have-to-add-and-multiply-huge-numbers-These-numbers-are-so-big-that-you-can-t-
In this problem, you have to add and multiply huge numbers! These numbers are so big that you can't contain them in any ordinary data types like a long integer.

import java.util.*;
import java.math.BigInteger;

public class method
{
   public static void main(String []args)
   {
       Scanner sc=new Scanner(System.in);
       String n1,n2;
       n1=sc.nextLine();
       n2=sc.nextLine();
       BigInteger bign1=new BigInteger(n1);
       BigInteger bign2=new BigInteger(n2);
       System.out.println(bign1.add(bign2));
       System.out.println(bign1.multiply(bign2));   
   }
}
