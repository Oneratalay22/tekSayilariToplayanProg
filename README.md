import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int n;  //Kullanıcıdan değer istiyoruz
        int total = 0;
        Scanner src = new Scanner(System.in);

        do {
            System.out.print("Lütfen sayı giriniz:");
            n = src.nextInt();  //Kullanıcıdan değer alıyoruz
            if (n % 2 == 1) {   //Burada tek sayılara ulaşabilmek için 2 ye bölümünden kalanın 1 olması gerekıyor
                total += n;
            }
        } while (n > 0);
        System.out.println("Toplam:" + total);
    }
}
