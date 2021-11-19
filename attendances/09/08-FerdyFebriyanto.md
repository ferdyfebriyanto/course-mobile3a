# Rangkuman Pertemuan 9

<hr>

* Nama      : Ferdy Febriyanto
* NIM       : 1941720007
* Kelas     : TI3A
* Pertemuan : 9 (Sembilan)

<hr>

* Pertemuan kali ini membahas tentang Data Storage,Shared Preference,Room, Live Data, View Model. pemrograman android proses menyimpan data dapat dilakukan dengan beberapa cara. Cara yang umum digunakan ada 5 yaitu dengan Shared Preferences, Internal Storage, External Storage, SQLite Database, dan Content Providers.

## Data Storage

* Preferensi Bersama — Data primitif pribadi dalam pasangan nilai kunci

* Penyimpanan Internal — Data pribadi di memori perangkat

* Penyimpanan Eksternal — Data publik di perangkat atau penyimpanan eksternal

* Database SQLite — Data terstruktur dalam database pribadi

* Penyedia Konten — Simpan secara pribadi dan sediakan untuk umum


## Menyimpan data di luar android

* Koneksi Jaringan—Di web dengan server Anda sendiri

* Cloud Backup—Mencadangkan aplikasi dan data pengguna di cloud

* Firebase Realtime Database—Menyimpan dan menyinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime


## Files

* Penyimpanan eksternal -- Direktori publik

* Penyimpanan internal -- Direktori pribadi hanya untuk aplikasi Anda

## Aplikasi dapat menelusuri struktur direktori

## Struktur dan operasi mirip dengan Linux dan java.io


## Preferensi Bersama

* Membaca dan menulis sejumlah kecil data primitif sebagai pasangan kunci/nilai ke file di penyimpanan perangkat Kelas SharedPreference menyediakan API untuk membaca, menulis, dan mengelola data ini Simpan data di onPause() pulihkan di onCreate()

* Hanya perlu satu file Preferensi Bersama per aplikasi Beri nama dengan nama paket aplikasi Anda—unik dan mudah dikaitkan dengan aplikasi Argumen MODE untuk getSharedPreferences() adalah untuk kompatibilitas mundur—gunakan hanya MODE_PRIVATE agar aman


## Database SQLite Menyimpan data dalam tabel baris dan kolom (spreadsheet…)

    Field = perpotongan antara baris dan kolom

    Bidang berisi data, referensi ke bidang lain, atau referensi ke tabel lain Baris diidentifikasi oleh ID unik Nama kolom unik per table


## Architecture component

    Kumpulan pustaka Android untuk menyusun aplikasi Anda dengan cara yang kuat, dapat diuji, dan dapat dipelihara.


## Room overview

    Room adalah perpustakaan pemetaan objek SQL yang kuat Menghasilkan kode Android SQLite Menyediakan API sederhana untuk database Anda


## Data access object

    Metode DAO menyediakan akses abstrak ke database aplikasi Sumber data untuk metode ini adalah objek entitas DAO harus antarmuka atau kelas abstrak menggunakan DAO untuk membuat API bersih untuk kode Anda