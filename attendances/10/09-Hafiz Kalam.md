Absensi Pertemuan 10
Rangkuman materi Retrofit dan Rest

Nama : Hafiz Kalam
NIM  : 1941720101

Retrofit adalah Sebuah library Android untuk melakukan request ke sebuah endpoint REST API.Library ini dikembangkan oleh sebuah perusahaan di Amerika bernama Square, Inc. (squareup.com).Library ini bersifat Open Source, sehingga kode-kodenya bebas diakses di GitHub. Minimal menggunakan Java 8+ atau Android 5.0 API 21+ (Lollipop)

Cara Penggunaan Retrofit 

- Berikan akses internet ke AndroidManifest.xml 
- Tambahkan library Retrofit di build.gradle dan converternya serta compileOptions 
- Siapkan server REST API atau dapat menggunakan yang sudah ada 
- Membuat class interface yang berisi method untuk mengakses REST API 
- Membuat class model atau Plain Old Java Object (POJO) untuk menampung data API.
- 	Membuat request ke REST API dengan Retrofit dan service yang telah dibuat. 

REST

Representational State Transfer (REST) adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services.
Terdiri dari method: GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS. REST memiliki 6 prinsip, yaitu client-server, stateless, cacheable, uniform interface, layered system, dan code on demand.

Prinsip REST

-Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.

-Stateless: tidak perlu session, hanya ada di sisi client.

-Cacheable: respon/request dapat disimpan dan digunakan kembali.

-Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.

-Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.

-Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.