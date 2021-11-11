Nama        : Irfan Thalib A
No Absen    : 11
NIM         : 1941720039
RANGKUMAN PERTEMUAN KE-10
Pertemuan kali ini membahas tentang Retrofit.
Retrofit adalah sebuah library Android untuk melakukan request ke sebuah endpoint REST API. Library ini dikembangkan oleh sebuah perusahaan di Amerika bernama Square, Inc. (squareup.com).
Retrofi dibuat karena developer seringkali bertemu masalah yang penyelesaiannya sebagi berikut:
Untuk mengakses REST API di Android, masih sulit dengan membuat banyak worker dan thread menggunakan Async Task.
Butuh akses dengan security yang baik.
Membuat koneksi dengan Async Task.
Pekerjaan terkait networking dapat dibantu dengan library Retrofit.
REST atau REpresentational State Transfer adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services.
RSET terdiri dari method method seperti : GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS
REST memiliki 6 prinsip, yaitu:
Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.
Stateless: tidak perlu session, hanya ada di sisi client.
Cacheable: respon/request dapat disimpan dan digunakan kembali.
Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.
Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.
Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.