# Vucut-Kitle-ndexi
www.patika.dev


*



        import java.util.Scanner;

        public class Vucutkitle {
        public static void main(String[] args) {
        double kilo,boy,sonuc;
        System.out.println("Lutfen kilonuzu giriniz:");
        Scanner kilo2 =new Scanner(System.in);
        kilo=kilo2.nextDouble();
        System.out.println("Lutfen boyunuzu giriniz:");
        Scanner boy2 =new Scanner(System.in);
        boy=boy2.nextDouble();
        sonuc=kilo/(boy*boy);
        System.out.println("Vucut kitle indeksiniz:"+sonuc);
    }
}
