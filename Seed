import java.util.Scanner;
public class Seed
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int num1=sc.nextInt();
        int num2=sc.nextInt();
        int seed=num1;
        String str1=String.valueOf(num1);
        for(int i=0;i<str1.length();i++)
        {
            int num=Character.getNumericValue(str1.charAt(i));
            seed=seed*num;
        }
        if(seed==num2)
        {
            System.out.println("Seed");
        }
        else
        {
            System.out.println("Not Seed");
        }
    }
}
