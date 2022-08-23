# Dairenin-Alan-n-ve-evresini-Hesaplayan-Program
import java.util.Locale;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

    int r;
    double pi = 3.14;
    Scanner inp = new Scanner(System.in).useLocale(Locale.US);

    System.out.print("r\'yi Giriniz : ");
    r = inp.nextInt();

    System.out.print("pi\'yi Griniz : ");
    pi = inp.nextDouble();

    double Alan = pi * r * r;
    double cevre = 2 * pi * r;

    System.out.println("Alanı : " + Alan);
    System.out.print("Çevresi : " + cevre);
