# taksi-kilometre-hesabi.
import java.util.Scanner;

public class kilometre {
    public static void main (String[]args){
        double kilometre , tutar;

        Scanner input = new Scanner(System.in);
        System.out.print("kilometre giriniz: ");
        kilometre= input.nextInt();

        tutar = 10+ (kilometre*2.20);
        tutar = (tutar <20 )?20:tutar;
        System.out.print(" Tutar : " + tutar);
    }
}
