# Tugas 1: Dasar-Dasar JavaScript

## Deskripsi
Tugas pertama ini akan membantumu memahami konsep dasar JavaScript seperti variabel, tipe data, operator, dan struktur kontrol dasar.

## Tugas Utama
Buatlah file JavaScript baru bernama `kalkulator.js` yang berisi program kalkulator interaktif dengan fitur-fitur berikut:

1. Minta input dua angka dari pengguna menggunakan `readline-sync` atau `prompt-sync`
2. Lakukan validasi input (pastikan input berupa angka)
3. Tampilkan menu pilihan operasi:
   - Penjumlahan (+)
   - Pengurangan (-)
   - Perkalian (*)
   - Pembagian (/)
   - Modulus (%)
   - Pangkat (**)
4. Lakukan operasi yang dipilih
5. Validasi untuk mencegah pembagian dengan nol
6. Tampilkan hasil operasi dengan format yang rapi menggunakan template literals
7. Tanyakan kepada pengguna apakah ingin melakukan perhitungan lagi

## Contoh Output
```
=== Kalkulator Sederhana ===
Masukkan angka pertama: 10
Masukkan angka kedua: 5

Pilih operasi:
1. Penjumlahan (+)
2. Pengurangan (-)
3. Perkalian (*)
4. Pembagian (/)
5. Modulus (%)
6. Pangkat (**)

Pilihan Anda (1-6): 1

Hasil: 10 + 5 = 15

Apakah ingin menghitung lagi? (y/n): n
Terima kasih telah menggunakan kalkulator ini!
```

## Langkah Pengerjaan
1. Install package `readline-sync` dengan perintah `npm install readline-sync`
2. Buat file `kalkulator.js` di folder ini
3. Tulis kode sesuai petunjuk di atas
4. Jalankan file dengan perintah `node kalkulator.js`
5. Uji berbagai skenario input untuk memastikan program berjalan dengan benar

## Tantangan Tambahan (Opsional)
1. Tambahkan fitur riwayat perhitungan yang menampilkan daftar semua operasi yang telah dilakukan
2. Implementasikan kalkulator dengan antarmuka berbasis web menggunakan HTML, CSS, dan JavaScript
3. Tambahkan fitur konversi satuan (suhu, panjang, berat, dll.)
4. Buat versi kalkulator ilmiah dengan fungsi-fungsi tambahan seperti akar, logaritma, trigonometri
5. Implementasikan error handling yang lebih baik untuk menangani berbagai skenario error

## Referensi
- [JavaScript Variables](https://www.w3schools.com/js/js_variables.asp)
- [JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)
- [JavaScript Template Literals](https://www.w3schools.com/js/js_string_templates.asp)
