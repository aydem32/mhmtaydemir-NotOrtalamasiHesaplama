import java.util.Scanner;

public class NotOrtalamasiHesaplama {

    public static void main (String[] args) {

        //  Matematik, Fizik, Kimya, Türkçe, Tarih, Müzik derslerinin sınav puanlarını kullanıcıdan alan ve
        //  ortalamalarını hesaplayıp ekrana bastırılan programı yazın.

        int mat,fiz,kim,turkce,muzik,tarih;
        int Topla;
        double sonuc;

        Scanner veriAl = new Scanner(System.in);

        System.out.println("Matematik Notunuzu Giriniz");
        mat = veriAl.nextInt();
        System.out.println("Fizik Notunuzu Giriniz");
        fiz = veriAl.nextInt();
        System.out.println("Kimya Notunuzu Giriniz");
        kim = veriAl.nextInt();
        System.out.println("Tükçe Notunuzu Giriniz");
        turkce = veriAl.nextInt();
        System.out.println("Tarih Notunuzu Giriniz");
        tarih = veriAl.nextInt();
        System.out.println("Müzik Notunuzu Giriniz");
        muzik = veriAl.nextInt();

        Topla = mat+fiz+kim+tarih+turkce+muzik;
        sonuc = Topla/6;

        System.out.println("Not Ortalamanız = "+sonuc);

    }
