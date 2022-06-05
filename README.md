# Not-Ortalamas-Hesaplayan-Program

import java.util.Scanner;
public class proje {
    private static int b;

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.println("Matematik notunuzu giriniz");
        int mat = input.nextInt();
        System.out.println("Fizik notunuzu giriniz");
        int fizik = input.nextInt();
        System.out.println("Kimya notunuzu giriniz");
        int kimya = input.nextInt();
        System.out.println("Turkce notunuzu giriniz");
        int turkce = input.nextInt();
        System.out.println("Tarih notunuzu giriniz");
        int tarih = input.nextInt();
        System.out.println("Muzik notunuzu giriniz");
        int muzik = input.nextInt();


        double ortalama = (mat+fizik+kimya+turkce+tarih+muzik)/6;

        boolean kosul = (ortalama > 60);


        System.out.println(kosul ? "Sinifi gecti":"Sinifta Kaldı");


    }


}
