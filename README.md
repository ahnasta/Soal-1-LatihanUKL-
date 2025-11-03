## Program (1) : Menentukan Ongkir Produk Berdasarkan Berat, Volume, dan Jarak Tempuh

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

## Contoh Input Output Program

<img width="1695" height="321" alt="ongkir" src="https://github.com/user-attachments/assets/85b99469-1f21-4ff6-b5fd-88681a2c2ec0" />


# 🔢 Program (2) : Menentukan Bilangan Ganjil atau Genap

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

## Contoh Input Output Program

<img width="1706" height="301" alt="ganjil genap" src="https://github.com/user-attachments/assets/3877787a-5f8b-46b5-a209-90e9060409c0" />

