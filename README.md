## Soal (1)

Sebuah perusahaan ekspedisi ternama mengirimkan paket-paket ke berbagai daerah. Biaya pengiriman tergantung pada berat paket, jarak tempuh serta volume barang.
Berikut adalah detail biaya pengiriman per kilogram:
    Jarak kurang dari atau sama dengan 10 km: Rp 4250 per kg
    Jarak lebih dari 10 km: Rp 6000 per kg
    Volume paket akan dikenakan biaya Rp 50.000,- ketika volume melebihi 100 cm^3. 
Buatlah sebuah program dalam bahasa Java untuk menghitung biaya total pengiriman berdasarkan berat paket jarak tempuh serta volume barang yang diketahui dengan menginputkan panjang, lebar serta tinggi dari paket.


## Program : Menentukan Ongkir Produk Berdasarkan Berat, Volume, dan Jarak Tempuh

## 📖 Deskripsi
Program ini dimanfaatkan untuk memperhitungkan **biaya ongkir paket** ke konsumen sesuai dengan ketentuan yang telah tercantum.
Pengguna diharapkan mengisi format yang telah ditampilkan oleh program sesuai dengan keterangan product yang dipilih serta memasukkan jarak tempuh lokasi pengirim ke penerima, setelah pengguna mengisi semua format dari program maka program akan secara otomatis menghitunng sesuai dengan bilangan yang telah dimasukkan oleh pengguna 

## ⚙️ Fitur Program
- Menghitung volume paket dari input panjang × lebar × tinggi
- Menentukan biaya per kilogram berdasarkan jarak pengiriman  
- Menambahkan biaya tambahan untuk volume besar
- Menampilkan rincian biaya secara lengkap dan terstruktur

## 🧠 Logika Program
1. Pengguna memasukkan nilai panjang, lebar, tinggi (cm), berat (kg), dan jarak (km).  
2. Program menghitung volume paket dengan rumus:
     **volume = panjang * lebar * tinggi**
3. Jika jarak ≤ 10 km, biaya/kg = Rp 4.250,-
   Jika jarak > 10 km, biaya/kg = Rp 6.000,-  
4. Jika volume > 100 cm³, maka dikenakan tambahan biaya Rp 50.000,- 
5. Total biaya dihitung dengan rumus:
    **total = (berat * biayaPerKg) + biayaTambahan**

## 💻 Cuplikan Kode
``java

double volume = panjang * lebar * tinggi;
        double biayaPerKg = (jarak <= 10) ? 4250 : 6000;
        double total = berat * biayaPerKg;
     if (volume > 100) {
        total += 50000;
    }


## Contoh Input Output Program

**Input** 
Masukkan panjang paket (cm): 10
Masukkan lebar paket (cm): 5
Masukkan tinggi paket (cm): 4
Masukkan berat paket (kg): 2
Masukkan jarak pengiriman (km): 8

**Output**
             ===== Perhitungan Ongkir Paket =====    
Volume paket: 200.0 cm³
Biaya per kg: Rp 4250.0
Biaya dasar: Rp 8500.0
Biaya tambahan volume: Rp 50000.0
----------------------------------
Total biaya pengiriman: Rp 58500.0




## Soal (2)

Buatlah sebuah program dalam bahasa Java untuk menentukan apakah suatu bilangan yang dimasukkan pengguna adalah bilangan ganjil atau genap


# 🔢 Program Menentukan Bilangan Ganjil atau Genap

## 📖 Deskripsi
Program ini bekerja dalam menentukan apakah sebuah **bilangan yang dimasukkan oleh pengguna** termasuk **bilangan ganjil** atau **bilangan genap** dengan menggunakan **konsep operator modulus (%)** untuk memeriksa sisa hasil pembagian bilangan dengan angka 2

## ⚙️ Fitur Program
- Menerima input satu bilangan dari pengguna
- Memeriksa apakah bilangan tersebut ganjil atau genap  
- Menampilkan hasil penentuan secara otomatis

## 🧠 Logika Program
1. Pengguna memasukkan sebuah bilangan bulat
2. Program menghitung sisa hasil pembagian dengan 2:
       **sisa = bilangan % 2**
3. Jika sisa == 0, maka bilangan adalah **genap**.  
4. Jika sisa != 0, maka bilangan adalah **ganjil**.  
5. Program menampilkan hasil sesuai kondisi

## 💻 Cuplikan Kode
``java
        
if (angka % 2 == 0) {
    System.out.println(angka + " adalah bilangan genap");
} else {
    System.out.println(angka + " adalah bilangan ganjil");
  }
 }
}

## Contoh Input Output Program

**Input**
Masukkan angka:
2

**Output**
2 adalah bilangan genap

**Input**
Masukkan angka:
3

**Output**
3 adalah bilangan ganjil
