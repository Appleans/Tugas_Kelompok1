# Tugas_Kelompok1
public class praktikumpemograman {
    // Method untuk menghitung jumlah dua bilangan bulat
    public static int getTotal(int num1, int num2) {
      return num1 + num2;
  }

  // Method utama (main)
  public static void main(String[] args) {
      // Menentukan dua bilangan bulat
      int bilangan1 = 8;
      int bilangan2 = 2;

      // Memanggil metode getTotal yang mencetak hasilnya
      int hasil = getTotal(bilangan1, bilangan2);
      System.out.println("Penjumlah " + bilangan1 + " & " + bilangan2 + " adalah: " + hasil);
  }
}
