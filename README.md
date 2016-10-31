import java.util.Scanner;
public class postcode
{
  public static void main (String [] arg){
      Scanner input = new Scanner (System.in);
      System.out.println ("Please enter your Postcode");
      String postCode = input.nextLine();
      System.out.println(postCode.toUpperCase());
    }
}
