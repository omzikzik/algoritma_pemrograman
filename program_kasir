package bonusprogramkasir;
import java.util.Scanner;
public class Bonusprogramkasir {

    public static void main(String[] args) {
        
        Scanner kasir = new Scanner (System.in);
        
        System.out.print("Nama Pembeli \t: ");
        String nama = kasir.nextLine();
        
        //jumlah barang
        System.out.print("Jumlah Telur \t: ");
        int telur = kasir.nextInt();
        System.out.print("Jumlah Tepung \t: ");
        int tepung = kasir.nextInt();
           
  	//harga barang
        int Htelur = (telur * 10000);
        int Htepung = (tepung * 5000);
        int total = (Htelur + Htepung);
        
        double diskon;
        if (total > 200000){
            diskon = (0.2 * total);
        } else if (total > 100000){
            diskon = (0.1 * total);
        } else {
            diskon = 0;
        }
        
        //jumlah akhir
        double bayar = total - diskon;
    
        System.out.println("===================================");
        System.out.println("====       PROGRAM KASIR       ====");
        System.out.println("===================================");    
        System.out.println("Nama pembeli \t: " + nama);
        System.out.println("===================================");
        System.out.println("Jumlah Telur \t: " + telur);
        System.out.println("Jumlah Tepung \t: " + tepung);        
        System.out.println("===================================");
        System.out.println("Harga Telur \t: " + Htelur);
        System.out.println("Harga Tepung \t: " + Htepung);        
        System.out.println("===================================");
        System.out.println("Total \t\t: " + total);
        System.out.println("Diskon \t\t: " + diskon);
        System.out.println("Total Akhir \t: " + bayar);
        System.out.println("===================================");
        System.out.println("            TERIMAKASIH            ");
    }
}
        
        
