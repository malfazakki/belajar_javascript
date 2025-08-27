# Tugas 2: Manajemen Data Mahasiswa dengan JavaScript

## Deskripsi
Tugas ini akan membantumu memahami konsep array, objek, dan fungsi-fungsi array seperti map, filter, dan reduce dalam JavaScript.

## Tugas Utama
Buatlah file `manajemenMahasiswa.js` yang berisi program untuk mengelola data mahasiswa dengan fitur-fitur berikut:

1. **Struktur Data**
   - Buat array of objects untuk menyimpan data mahasiswa
   - Setiap mahasiswa memiliki properti: NIM, nama, jurusan, nilai (array dari nilai-nilai)

2. **Fungsi yang Harus Dibuat**
   - `tambahMahasiswa(nim, nama, jurusan)`
   - `tambahNilai(nim, nilai)`
   - `hitungRataRata(nim)`
   - `cariMahasiswa(nim)`
   - `tampilkanSemuaMahasiswa()`
   - `hapusMahasiswa(nim)`

3. **Fitur Tambahan**
   - Validasi input
   - Hitung IPK (Indeks Prestasi Kumulatif)
   - Tampilkan mahasiswa dengan nilai tertinggi/terendah
   - Tampilkan daftar mahasiswa berdasarkan jurusan

## Contoh Output
```
=== Aplikasi Manajemen Data Mahasiswa ===

1. Tambah Mahasiswa
2. Tambah Nilai
3. Tampilkan Semua Mahasiswa
4. Cari Mahasiswa
5. Hapus Mahasiswa
6. Keluar

Pilihan Anda: 1

Masukkan NIM: 12345
Masukkan Nama: Budi Santoso
Masukkan Jurusan: Teknik Informatika

Mahasiswa berhasil ditambahkan!
```

## Langkah Pengerjaan
1. Buat file `manajemenMahasiswa.js`
2. Buat array untuk menyimpan data mahasiswa
3. Implementasikan semua fungsi yang diminta
4. Buat menu interaktif menggunakan `readline-sync`
5. Uji semua fitur yang telah dibuat

## Tantangan Tambahan (Opsional)
1. Simpan data ke file JSON menggunakan `fs` module
2. Load data dari file JSON saat aplikasi dimulai
3. Tambahkan fitur sorting (berdasarkan nama, NIM, atau IPK)
4. Buat antarmuka web sederhana menggunakan Express.js
5. Tambahkan validasi yang lebih ketat (contoh: format NIM, nilai antara 0-100)

## Referensi
- [JavaScript Arrays](https://www.w3schools.com/js/js_arrays.asp)
- [JavaScript Objects](https://www.w3schools.com/js/js_objects.asp)
- [Array Methods](https://www.w3schools.com/js/js_array_methods.asp)
