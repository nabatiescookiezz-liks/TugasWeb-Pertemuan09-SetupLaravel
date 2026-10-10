# Tugas Rutin 9 — Laravel Setup

## Deskripsi
Proyek ini dibuat untuk memenuhi tugas rutin mata kuliah dengan menggunakan framework Laravel dan database MySQL.

## Teknologi
- PHP
- Laravel
- MySQL
- Blade Template
- Composer

## Fitur
- Halaman Beranda
- Halaman Tentang
- Halaman Kontak
- Routing menggunakan Controller
- Tampilan dinamis menggunakan Blade
- Model Produk dan migration tabel produk

## Struktur Folder

```text
tugas-rutin9-laravel/
├── app/
│   ├── Http/Controllers/
│   │   └── PageController.php
│   └── Models/
│       └── Produk.php
├── database/
│   └── migrations/
├── resources/
│   └── views/
│       ├── home.blade.php
│       ├── about.blade.php
│       └── contact.blade.php
├── routes/
│   └── web.php
├── .env.example
├── artisan
├── composer.json
└── README.md
```

## Cara Instalasi

1. Pastikan PHP, Composer, dan MySQL sudah terpasang.
2. Clone repository proyek.
3. Masuk ke folder proyek.
4. Jalankan `composer install`.
5. Salin `.env.example` menjadi `.env`.
6. Sesuaikan konfigurasi database pada file `.env`.
7. Buat database MySQL bernama `tugas_rutin9_db`.
8. Jalankan `php artisan key:generate`.
9. Jalankan `php artisan migrate`.
10. Jalankan `php artisan serve`.
11. Buka `http://127.0.0.1:8000` di browser.

## Daftar Halaman

- `/` — Beranda
- `/about` — Tentang
- `/contact` — Kontak