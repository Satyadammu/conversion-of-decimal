# conversion-of-decimal
import java.util.*;
public class MyClass {
    public static void main(String args[])
    {
        
        Scanner sc=new Scanner (System.in);
        System.out.println("enter our choice:");
        int m=sc.nextInt();
        System.out.println("Enter input:");
        int n=sc.nextInt();
        switch (m)
        {
       
       case 1:
      {
       String h=Integer.toBinaryString(n);
       System.out.println("BinaryValue:"+h);
       } break;
       case 2:
      {
     String h=Integer.toOctalString(n);
     System.out.println("Octal value:"+h);
      } break;
       case 3:
     {
       String h =Integer.toHexString(n);
       System.out.println("Hexa value;"+h);
     }
} 
}
}
