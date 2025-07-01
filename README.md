Baik, ini adalah ringkasan langkah-langkah penting untuk menjalankan aplikasi "DATA KARYAWAN" dari NetBeans, dengan asumsi proyek dan file sudah tersedia:

**1. Siapkan Database (MySQL via XAMPP/WAMP/MAMP):**
    * **Mulai Server MySQL.**
    * **Akses phpMyAdmin** (`http://localhost/phpmyadmin`).
    * **Buat database** bernama `db_karyawan`.
    * **Buat tabel `tb_karyawan`** di dalam `db_karyawan` dengan struktur sesuai gambar (kolom `nik`, `nama`, `jabatan`, `alamat`, `email`, `no_telp`, dengan `nik` sebagai PRIMARY KEY).

**2. Buka & Jalankan di NetBeans:**
    * **Buka NetBeans IDE.**
    * **Buka Proyek Anda** (`RobyAlifiansyahPemrograman1`).
    * **Pastikan MySQL Connector/J JAR ada di "Libraries" proyek.** (Jika tidak, tambahkan).
    * **Periksa file koneksi database** (`KoneksiMysql.java`) untuk memastikan `db_karyawan`, `root`, dan password kosong (jika pakai XAMPP/WAMP/MAMP default) sudah benar.
    * **Klik kanan proyek > "Run"** (atau tombol Run di toolbar).

Aplikasi seharusnya akan terbuka dan terhubung ke database.
