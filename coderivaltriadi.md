# tugas-ASD-RivalTriadi
Rival Triadi_TI23 B_Tugas Membuat Program Menghitung Biaya Parkir_Algoritma dan Struktur Data
import java.util.Scanner;
public class MenghitungBiayaParkir {
    public static void main(String[] args) {
        Scanner masukkan_data = new Scanner(System.in);
        int tarif = 2000;
        int total_jam_parkir;
        int Hasil;

        System.out.println("SELAMAT DATANG DI EPARKIR");
        System.out.print("JAM MASUK");
        int jam_Masuk = masukkan_data.nextInt();
        System.out.println("JAM KELUAR");
        int jam_keluar = masukkan_data.nextInt();
        total_jam_parkir = jam_keluar-jam_Masuk;
        Hasil = total_jam_parkir*tarif;
        System.out.println("TOTAL YANG HARUS DIBAYAR RP" +Hasil);


    }
}
