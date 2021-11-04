Rizqy Ghaniyyu F / 18 / TI3A

Data Storage 
- Android File System -> Data primitif pribadi dalam pasangan nilai kunci.
- Internal Storage -> Data pribadi di memori perangkat.
- External Storage -> Data publik di perangkat atau penyimpanan eksternal.
- SQLite Database -> Data terstruktur dalam database pribadi
- Content Providers -> Simpan secara pribadi dan sediakan untuk umum.
- Network Connection -> Di web dengan server Anda sendiri.
- Cloud Backup -> Mencadangkan aplikasi dan data pengguna di cloud.
- Firebase Realtime Database -> Menyimpan dan menyinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime.

Internal Storage
Selalu tersedia. Menggunakan sistem file perangkat.Hanya aplikasi Anda yang dapat mengakses file, kecuali secara eksplisit diatur agar dapat dibaca atau ditulis. Saat mencopot pemasangan aplikasi, sistem menghapus semua file aplikasi dari penyimpanan internal.

External Storage 
Tidak selalu tersedia, dapat dihapus. Menggunakan sistem file perangkat atau penyimpanan eksternal fisik seperti kartu SD. Dapat dibaca dunia, sehingga aplikasi apa pun dapat membaca. Saat uninstall, sistem tidak menghapus file pribadi ke aplikasi.

SQLite Database
Ideal untuk data berulang atau terstruktur, seperti kontak. Android menyediakan database seperti SQL.Tercakup dalam bab dan praktik berikut. SQLite Primer.Pengantar Database SQLite.Penyimpanan Data SQLite Praktis. Mencari Praktis Database SQLite

Perbedaan antara Shared Preferences vs saved instance state 
Untuk Shared Preferences dapat mempertahankan data di seluruh sesi pengguna, bahkan jika aplikasi dimatikan dan dimulai ulang, atau perangkat di-boot ulang Data yang harus diingat di seluruh sesi, seperti pengaturan pilihan pengguna atau skor game mereka Penggunaan umum adalah untuk menyimpan preferensi pengguna Untuk Saved Instance State dapat Mempertahankan data status di seluruh instance aktivitas dalam sesi pengguna yang sama Data yang tidak boleh diingat di seluruh sesi, seperti tab yang dipilih saat ini atau status aktivitas saat ini. Penggunaan umum adalah untuk membuat ulang status setelah perangkat diputar

Pada Sqlite Primer terdapat dua bagian yaitu SQLite Database dan Queries yang nantinya akan diapakai pada SQLite Primer. Untuk Sqlite Database dan Queries yang digunakan pada umumnya sama dengan database database lain yang bisa digunakan untuk menyimpan data dan cara mengetahui query nya juga sama dalam penggunaanya. Dan dalam mengolah data tersebut untuk memunculkan kedalam tampilan android menggunakan Room, Live Data dan View Model.