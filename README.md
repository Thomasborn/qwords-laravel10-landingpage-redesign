# QWords Laravel 10 Landing Page Redesign

Projek ini adalah redesign dari landing page QWords menggunakan Laravel versi 10. Silakan ikuti langkah-langkah di bawah untuk menginstal dan menjalankan projek ini.

## Persyaratan Sistem
Pastikan sistem Anda memenuhi persyaratan berikut sebelum menginstal projek:

- PHP versi 8 atau lebih baru
- Composer (https://getcomposer.org/)
- Node.js dan npm (https://nodejs.org/)

## Langkah Instalasi

1. **Clone Repositori**

    ```bash
    git clone https://github.com/Thomasborn/qwords-laravel10-landingpage-redesign.git
    ```

2. **Pindah ke Direktori Projek**

    ```bash
    cd qwords-laravel10-landingpage-redesign
    ```

3. **Install Dependensi PHP**

    ```bash
    composer install
    ```

4. **Copy .env**

    Duplikat file `.env.example` dan simpan sebagai `.env`. Sesuaikan konfigurasi database dan pengaturan lainnya sesuai kebutuhan Anda.

5. **Generate App Key**

    ```bash
    php artisan key:generate
    ```

6. **Migrasi Database**

    ```bash
    php artisan migrate
    ```

7. **Install Dependensi JavaScript**

    ```bash
    npm install
    ```

8. **Compile Assets**

    ```bash
    npm run dev
    ```

9. **Jalankan Aplikasi**

    ```bash
    php artisan serve
    ```

    Akses aplikasi melalui browser pada [http://localhost:8000](http://localhost:8000).

## Catatan Tambahan

- Pastikan Anda telah mengatur koneksi database pada file `.env`.
- Pastikan direktori `storage` dan `bootstrap/cache` dapat ditulis oleh server web.
- Lihat dokumentasi Laravel resmi (https://laravel.com/docs) untuk informasi lebih lanjut.

Terima kasih telah menggunakan QWords Laravel 10 Landing Page Redesign!
