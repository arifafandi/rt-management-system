# Sistem Manajemen Perumahan

Aplikasi manajemen perumahan yang dirancang untuk membantu RT dalam mengelola administrasi perumahan, termasuk data penghuni, pembayaran iuran, dan pengeluaran.

## Repositori Terkait

Proyek ini terdiri dari dua repositori terpisah:

- [Backend Laravel](https://github.com/arifafandi/rt-management-system-backend) - API dan logika bisnis
- [Frontend React](https://github.com/arifafandi/rt-management-system-frontend) - Antarmuka pengguna

## Gambaran Umum

Aplikasi ini dibuat untuk membantu RT mengelola administrasi perumahan dengan 20 rumah (15 dihuni tetap dan 5 dihuni sementara/kontrak). Sistem mengelola:

- Data penghuni dan rumah
- Pembayaran iuran bulanan (satpam Rp100.000 dan kebersihan Rp15.000)
- Pengeluaran rutin dan non-rutin
- Laporan keuangan bulanan dan tahunan

## Entity Relationship Diagram

![Entity Relationship Diagram](./screenshots/erd.png)

## Fitur Utama

### 1. Dashboard

Dashboard menampilkan ringkasan status perumahan dan keuangan:
- Jumlah rumah yang dihuni/tidak dihuni
- Status pembayaran bulan ini
- Grafik pemasukan dan pengeluaran
- Saldo tahunan
![Dashboard](./screenshots/dashboard.png)

### 2. Pengelolaan Penghuni

Fitur untuk mengelola data penghuni:
- Daftar semua penghuni
![Daftar Penduduk](./screenshots/residents.png)
- Form tambah penghuni baru
![Tambah Penduduk](./screenshots/add-resident.png)
- Form edit data penghuni
![Tambah Penduduk](./screenshots/edit-resident.png)
- Lihat foto KTP
![Lihat foto KTP](/screenshots/show-ktp.png)

### 3. Pengelolaan Rumah

Fitur untuk mengelola data rumah dan penghuninya:
- Daftar semua rumah dengan status hunian
![Pengelolaan Rumah](/screenshots/houses.png)
- Form tambah/edit rumah
![Tambah Rumah](/screenshots/add-house.png)
![Edit Rumah](/screenshots/edit-house.png)
- Detail rumah
![Detail Rumah](/screenshots/house-detail.png)
- Riwayat penghuni
![Riwayat Penghuni](/screenshots/resident-history.png)
- Riwayat pembayaran setiap rumah
![Riwayat Pembayaran](/screenshots/payment-history.png)
- Manajemen penghuni
![Manajemen Penghuni](/screenshots/management-resident.png)


### 4. Pengelolaan Pembayaran

Fitur untuk mencatat dan melacak pembayaran iuran:
- Daftar semua pembayaran
![Pengelolaan Pembayaran](/screenshots/payments.png)
- Form tambah pembayaran baru
![Tambah Pembayaran](/screenshots/add-payment.png)
- Edit pembayaran
![Edit Pembayaran](/screenshots/edit-payment.png)

### 5. Pengelolaan Pengeluaran

Fitur untuk mencatat pengeluaran perumahan:
- Daftar semua pengeluaran
![Pengelolaan Pengeluaran](/screenshots/expenses.png)
- Form tambah pengeluaran baru
![Tambah Pengeluaran](/screenshots/add-expense.png)
- Form edit pengeluaran baru
![Edit Pengeluaran](/screenshots/edit-expense.png)

### 6. Laporan Keuangan

Fitur untuk melihat laporan keuangan perumahan:
- Ringkasan keuangan bulanan dan tahunan
![Laporan Keuangan](/screenshots/report-summary.png)
- Laporan bulanan pemasukan dan pengeluaran
![Laporan Keuangan Bulanan](/screenshots/report-monthly.png)
![Laporan Keuangan Bulanan](/screenshots/report-monthly-expense.png)


## Teknologi yang Digunakan

### Backend:
- PHP 8.2.16
- Laravel 10
- MySQL

### Frontend:
- Node.js v22.14.0
- React dengan Vite
- Material UI

## Persyaratan Sistem

- PHP 8.2.16 atau lebih tinggi
- Node.js v22.14.0 atau lebih tinggi
- MySQL
- Composer
- NPM atau Yarn (rekomdasi npm)

## Langkah Pengembangan

Untuk mengembangkan aplikasi ini:

1. Clone repositori backend dan frontend
2. Ikuti petunjuk instalasi di masing-masing README
3. Backend akan berjalan di http://localhost:8000
4. Frontend akan berjalan di http://localhost:5173