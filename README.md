Tech Stack :

Laravel: Laravel adalah kerangka kerja PHP yang populer dan open-source. Ini menyediakan berbagai fitur dan alat untuk mempercepat pengembangan aplikasi web, termasuk routing, manajemen basis data, dan otentikasi pengguna.

HTML: HTML adalah bahasa markup yang digunakan untuk membangun struktur dan konten halaman web. Ini digunakan untuk menentukan elemen seperti judul, paragraf, gambar, dan tautan.

CSS: CSS adalah bahasa gaya yang digunakan untuk mengatur tampilan halaman web. Ini digunakan untuk menentukan warna, font, ukuran, dan tata letak elemen pada halaman web.

JavaScript: JavaScript adalah bahasa pemrograman yang digunakan untuk memberikan interaksi dan fungsionalitas pada halaman web. Ini dapat digunakan untuk membuat efek animasi, validasi formulir, dan mengambil data dari server melalui AJAX.

AOS: AOS adalah singkatan dari "Animate On Scroll". Ini adalah library JavaScript open-source yang memungkinkan Anda membuat efek animasi ketika pengguna menggulir halaman web.

Langkah Menjalankan Projek

Buka halaman repositori proyek Laravel di GitHub.
Klik tombol "Code" atau "Clone" dan salin URL repositori proyek (misalnya, https://github.com/nama-akun/nama-repo.git).
Buka terminal atau command prompt di komputer Anda.
Pindah ke direktori tempat Anda ingin menyimpan proyek dengan menggunakan perintah cd nama-direktori.
Jalankan perintah git clone <URL repositori> untuk melakukan cloning proyek dari GitHub. Misalnya, git clone https://github.com/nama-akun/nama-repo.git.
Setelah proses cloning selesai, pindah ke direktori proyek dengan menggunakan perintah cd nama-repo.
Salin file .env.example dan ubah namanya menjadi .env.
Jalankan perintah composer install untuk menginstal semua dependensi proyek yang terdaftar di file composer.json.
Jalankan perintah php artisan key:generate untuk menghasilkan kunci aplikasi yang diperlukan oleh Laravel.
Buat database kosong di server MySQL atau database lain yang Anda gunakan.
Ubah pengaturan koneksi database di file .env dengan mengisi DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, dan DB_PASSWORD sesuai dengan konfigurasi server database Anda.
Jalankan perintah php artisan migrate untuk menjalankan migrasi dan membuat tabel-tabel yang diperlukan di database.
Jalankan perintah php artisan serve untuk menjalankan server pengembangan Laravel.
Buka browser dan akses http://localhost:8000 atau alamat yang ditampilkan di terminal untuk melihat proyek Laravel yang sedang berjalan.
Dengan langkah-langkah di atas, Anda seharusnya dapat melakukan cloning dan menjalankan proyek Laravel dari GitHub dengan sukses. Pastikan Anda memiliki lingkungan pengembangan yang sesuai (seperti PHP, Composer, dan server database) sebelum memulai.