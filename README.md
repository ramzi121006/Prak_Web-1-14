# Prak_Web-1-14
# Ramzi Tech News — Web Design Project

Selamat datang di repositori **Ramzi Tech News**. Website ini merupakan platform media informasi modern dengan implementasi tema warna netral maskulin (deep navy dan slate blue) yang menyajikan berbagai artikel seputar dunia Teknologi, Pemrograman, dan Berita Kampus. Proyek website ini dikembangkan menggunakan framework **CodeIgniter 4** dan mendukung pengelolaan data dinamis berbasis **AJAX**.

---

## Fitur Utama Website
* **Homepage Minimalis:** Tampilan beranda modern dengan kombinasi warna profesional yang bersih dan nyaman di mata.
* **Autentikasi Admin:** Sistem login aman untuk masuk ke panel kendali (dashboard) admin.
* **Manajemen Artikel (CRUD):** Admin memiliki akses penuh untuk menambah, melihat, mengubah, dan menghapus artikel.
* **AJAX Mode Integration:** Pengelolaan data artikel secara real-time tanpa perlu memuat ulang (refresh) halaman.
* **Responsif dan UI Modern:** Tata letak grid yang rapi untuk memudahkan pengguna dalam menjelajahi konten berita.

---

## Teknologi yang Digunakan
* **Framework:** CodeIgniter 4 (PHP)
* **Database:** MySQL
* **Frontend:** HTML5, CSS3 (Custom Navigation Styles), JavaScript (AJAX)
* **Server Lokal:** XAMPP

---

## Dokumentasi Antarmuka (Screenshots)

Berikut adalah alur sistem dan tampilan fitur dari website yang telah diselesaikan:

### 1. Halaman Utama (Beranda Pengunjung)
Tampilan awal website saat pertama kali diakses oleh pengguna umum.
![Halaman Utama](https://github.com/ramzi121006/Prak_Web-1-14/blob/0c53e6e805889d0d950e9771cebc4c8b08767860/hasil%20prak%201-14/1%20halaman%20home.jpeg)

### 2. Form Login Admin
Halaman gerbang masuk khusus bagi admin untuk mengotentikasi akun sebelum mengelola konten.
![Login Admin](https://github.com/ramzi121006/Prak_Web-1-14/blob/b0f49da539e516253282d461549b0670266e878d/hasil%20prak%201-14/2%20halaman%20login.jpeg)

### 3. Dashboard Panel Admin
Halaman utama panel kendali admin yang menampilkan tabel data artikel utama.
![Dashboard Admin](3_dashboard_panel_admin.png)

### 4. Form Tambah Artikel Baru
Fasilitas input bagi admin untuk memasukkan judul, kategori, gambar utama, serta konten berita baru.
![Tambah Artikel](https://github.com/ramzi121006/Prak_Web-1-14/blob/f4f4b5271bfd995490832a7ee2b53df83ef9041b/hasil%20prak%201-14/3%20dasrboard%20admin.jpeg)

### 5. Notifikasi Sukses Tambah Artikel
Validasi visual dari sistem berupa bar notifikasi hijau saat artikel baru berhasil masuk ke database.
![Artikel Sukses](https://github.com/ramzi121006/Prak_Web-1-14/blob/dc1669f73c4367e2fc0411ea82bc2fbe51e76dce/hasil%20prak%201-14/5%20artikel%20berhasil%20di%20tambah.jpeg)

### 6. Daftar Artikel Sisi User
Tampilan kartu artikel yang diperbarui secara dinamis pada halaman depan pengunjung.
![Daftar Artikel User](https://github.com/ramzi121006/Prak_Web-1-14/blob/e0bb6ef3edb90a7f8b812e039283afe3ed2cb8d5/hasil%20prak%201-14/6%20halaman%20daftar%20artikel.jpeg)

### 7. Manajemen Artikel Ter-update (AJAX Mode)
Tampilan tabel manajemen data pada menu AJAX yang otomatis memperbarui daftar artikel secara real-time.
![Manajemen AJAX](https://github.com/ramzi121006/Prak_Web-1-14/blob/50ecc25e92f32ec0cbe3ea8737c569f9dd82d7a8/hasil%20prak%201-14/7%20halaman%20ajax%20mode.jpeg)

### 8. Halaman Baca Detail Konten
Tampilan penuh artikel saat pengunjung mengklik opsi "Baca Selengkapnya" untuk membaca konten secara utuh.
![Detail Artikel](https://github.com/ramzi121006/Prak_Web-1-14/blob/a8e184c8c964039868eba0dd8ae0c482695ba0a8/hasil%20prak%201-14/8%20detail%20artikel.jpeg)

---

## Cara Menjalankan Proyek di Lokal
1. **Clone Repositori:**
```bash
   git clone [https://github.com/username-valentino/nama-repo-kamu.git](https://github.com/username-valentino/nama-repo-kamu.git)

Aktifkan XAMPP:
Buka XAMPP Control Panel, kemudian aktifkan modul Apache dan MySQL.

Konfigurasi Database:

Akses halaman localhost/phpmyadmin di browser.

Buat database baru dan import file .sql bawaan proyek ini.

Sesuaikan kredensial dan pengaturan database pada file .env.

Jalankan Lokal Server:
Buka terminal pada text editor (VS Code), lalu jalankan perintah:

Bash
   php spark serve
Akses Website:
Buka browser pilihan Anda dan akses alamat http://localhost:8080.
