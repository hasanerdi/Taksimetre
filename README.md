# Taksimetre
import java.util.Scanner;

public class Taksimetre {
    public static void main(String[] args) {

        //değişkenler;
        double gidilenKM, cikanpara, kmbasinapara ;
        int baslamaUcreti = 10 ;


        //scanner ve verileri al
        Scanner girilenler = new Scanner(System.in);
        System.out.print(" Gidilen  KM  ");
        gidilenKM = girilenler.nextDouble();


        cikanpara = (gidilenKM * 2.20 ) ;
        cikanpara += baslamaUcreti ;
        cikanpara = (cikanpara < 20 ) ? 20 : cikanpara ;
        System.out.println(" kmbasinapara = 2.20 den Çıkanpara " + cikanpara);
