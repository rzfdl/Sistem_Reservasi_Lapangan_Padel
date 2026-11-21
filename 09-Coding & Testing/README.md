# 09 - Coding & Testing: Padelku (Implementasi)

Implementasi Sistem Reservasi Lapangan Padel dengan Laravel 12, PHP 8.2, dan MySQL.
Kode ada di `padelku-RPL.zip`.

## Cara menjalankan
1. Ekstrak `padelku-RPL.zip`, lalu buka foldernya di terminal.
2. `composer install`
3. `copy .env.example .env`
4. Buat database kosong bernama `padelku` di MySQL (XAMPP/phpMyAdmin).
5. `php artisan key:generate`
6. `php artisan migrate --seed`
7. `php artisan serve`, lalu buka http://127.0.0.1:8000

## Akun contoh
| Peran | Username | Password |
|---|---|---|
| Admin | admin | admin123 |
| Pelanggan | dimas | password |

## Fitur
Login, jadwal lapangan (tanpa login), reservasi, upload bukti pembayaran,
status reservasi, manajemen lapangan, verifikasi pembayaran, dan laporan transaksi.
