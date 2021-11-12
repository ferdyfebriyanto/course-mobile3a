Absensi Pertemuan ke-10

Pada pertemuan ke-10 membahasi tentang retrofit dan rest
Retrofit adalah Sebuah library Android untuk melakukan request ke sebuah endpoint REST API.Library ini dikembangkan oleh sebuah perusahaan di Amerika bernama Square, Inc. (squareup.com).Library ini bersifat Open Source, sehingga kode-kodenya bebas diakses di GitHub .Minimal menggunakan Java 8+ atau Android 5.0 API 21+ (Lollipop)
Kenapa harus menggunakan retrofit?
-Untuk mengakses REST API di Android, masih sulit dengan membuat banyak worker dan thread menggunakan Async Task.
-Butuh akses dengan security yang baik.
-Membuat koneksi dengan Async Task tidak mudah.
-Maka lebih baik pekerjaan terkait networking dapat dibantu dengan library Retrofit.

REST
Dikenal pertama kali oleh seorang computer scientist dari Amerika bernama Roy Thomas Fielding dalam disertasinya pada tahun 2000 yang berjudul “Architectural Styles and the Design of Network-based Software Architecures”.
Dia adalah salah satu penemu juga dalam teknologi HTTP dan seorang co-founder di perusahaan Apache HTTP Service.
REpresentational State Transfer (REST) adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services.
Terdiri dari method: GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS
REST memiliki 6 prinsip, yaitu client-server, stateless, cacheable, uniform interface, layered system, dan code on demand.

prinsip REST
-Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.
-Stateless: tidak perlu session, hanya ada di sisi client.
-Cacheable: respon/request dapat disimpan dan digunakan kembali.
-Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.
-Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.
-Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.
