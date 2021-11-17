ABSENSI PERTEMUAN KE-10
Pertemuan kali ini membahas tentang Retrofit.
Reftrofit adalah sebuah library yang dapat digunakan di Android untuk membuat request ke
sebuah endpoint REST API. Library ini dikembangkan oleh sebuah perusahaan di Amerika
bernama Square, Inc. (squareup.com). Library ini bersifat Open Source, sehingga kodekodenya bebas diakses di GitHub (https://github.com/square/retrofit). Halaman resmi untuk
Retrofit dapat diakses melalui tautan: https://square.github.io/retrofit/Retrofi dibuat karena developer seringkali bertemu masalah yang penyelesaiannya sebagi berikut:
Uerikan akses internet ke AndroidManifest.xml
Tambahkan library Retrofit di build.gradle dan converternya serta compileOptions
Siapkan server REST API atau dapat menggunakan yang sudah ada
Membuat class interface yang berisi method untuk mengakses REST API
Membuat class model atau Plain Old Java Object (POJO) untuk menampung data API.
Bisa memanfaatkan tool berikut: www.jsonschema2pojo.org
Membuat request ke REST API dengan Retrofit dan service yang telah dibuat.
Membuat koneksi dengan Async Task.
Pekerjaan terkait networking dapat dibantu dengan library Retrofit.
REST atau REpresentational State Transfer adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services.
RSET terdiri dari method method seperti : GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS
REST memiliki 6 prinsip, yaitu:
Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.
Stateless: tidak perlu session, hanya ada di sisi client.
Cacheable: respon/request dapat disimpan dan digunakan kembali.
Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.

