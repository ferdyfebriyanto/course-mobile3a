Nama    : Hisyam Haryo Mahdyan
Kelas   : TI-3A
NIM     : 1941720186

Pada pertemuan 10 membahas tentang Retrofit lalu dilanjutkan dengan pengerjaan jobsheet.

##Apa Itu Retrofit

Reftrofit adalah sebuah library yang dapat digunakan di Android untuk membuat request ke
sebuah endpoint REST API. Library ini dikembangkan oleh sebuah perusahaan di Amerika
bernama Square, Inc. (squareup.com). Library ini bersifat Open Source, sehingga kodekodenya
bebas diakses di GitHub (https://github.com/square/retrofit). Halaman resmi untuk
Retrofit dapat diakses melalui tautan: https://square.github.io/retrofit/. 

##Cara Penggunaan Retrofit

Untuk menggunakan library Retrofit, Anda dapat melakukannya dengan langkah-langkah
berikut ini:
1. Berikan akses internet ke AndroidManifest.xml
2. Tambahkan library Retrofit di build.gradle dan converternya serta compileOptions
3. Siapkan server REST API atau dapat menggunakan yang sudah ada
4. Membuat class interface yang berisi method untuk mengakses REST API
5. Membuat class model atau Plain Old Java Object (POJO) untuk menampung data API. Bisa memanfaatkan tool berikut: www.jsonschema2pojo.org
6. Membuat request ke REST API dengan Retrofit dan service yang telah dibuat.