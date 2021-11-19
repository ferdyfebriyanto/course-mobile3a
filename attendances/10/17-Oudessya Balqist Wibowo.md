# Retrofit

Reftrofit adalah sebuah library yang dapat digunakan di Android untuk membuat request ke
sebuah endpoint REST API. Library ini dikembangkan oleh sebuah perusahaan di Amerika
bernama Square, Inc. (squareup.com). Library ini bersifat Open Source. 

## Cara Penggunaan Retrofit 

- Berikan akses internet ke AndroidManifest.xml

- Tambahkan library Retrofit di build.gradle dan converternya serta compileOptions

- Siapkan server REST API atau dapat menggunakan yang sudah ada

- Membuat class interface yang berisi method untuk mengakses REST API

- Membuat class model atau Plain Old Java Object (POJO) untuk menampung data API.

- Bisa memanfaatkan tool berikut: www.jsonschema2pojo.org

- Membuat request ke REST API dengan Retrofit dan service yang telah dibuat.

## Rest 

REST adalah singkatan dari REpresentational State Transfer. REST merupakan gaya arsitektur untuk menyediakan standar antara sistem komputer sehingga memudahkan sistem untuk berkomunikasi satu sama lain. REST, sering disebut sistem RESTful, dicirikan oleh sifatnya yang stateless dan dapat memisahkan masalah klien dan server. Stateless artinya server tidak perlu mengetahui apa pun tentang status klien dan sebaliknya. Sehingga, baik server maupun klien dapat memahami pesan apa pun yang diterima, bahkan tanpa melihat pesan sebelumnya.

REST menggunakan serangkaian metode permintaan standar termasuk GET, POST, PUT, DELETE.

Pada intinya, REST terdiri dari empat hal berikut

- Sumber daya yang direferensikan oleh pengenal global seperti URI.

- Representasi sumber daya, yaitu dokumen yang berisi informasi sumber daya yang dibutuhkan.

- Komponen yang berkomunikasi satu sama lain antara klien dan server.

- Interface standar yang mengidentifikasi sumber daya, memungkinkan manipulasi sumber daya melalui representasi, termasuk pesan deskriptif mandiri yang menjelaskan cara memproses permintaan dan respons, dan hypermedia yang diidentifikasi secara dinamis.

### Prinsip Dasar REST

1. Client-Server

2. Stateless

3. Cacheable

4. Interface yang seragam 

5. Sistem yang berlapis 

6. Code on demand yang opsional 


