# Armstrong-sayi-bulma
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
       Scanner scanner = new Scanner(System.in);
       System.out.print("Bir sayı girin: ");
       int sayi = scanner.nextInt();
       int toplam = 0;
       int temp = Math.abs(sayi);

       while (temp > 0) {
           toplam += temp % 10;
           temp /= 10;
       }
       System.out.println("Basamak toplamı: " + toplam);
    }
}
