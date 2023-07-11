# taksimetre
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int km;

        double perkm= 2.20, total, startprice= 10 ;

        Scanner input = new Scanner(System.in);
System.out.println("mesafeyi km olarak giriniz: ");

km= input.nextInt();
total= perkm*km+startprice;

        total=(total<20)? 20:total;
        System.out.println("taksimetre diyor ki: " + total);


    }
}
