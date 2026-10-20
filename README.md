# 📘 LAPORAN PRAKTIKUM 3
## Pemrograman Berbasis Web (PBW)

<p align="center">
  <b>LaraPress — Website Informasi Berbasis Laravel</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/HTML5-Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
</p>

---

## 👨‍🎓 Identitas Mahasiswa

| Informasi | Keterangan |
|---|---|
| Nama | Ridwan Odi Nugroho |
| NIM | 4524210089 |
| Program Studi | Teknik Informatika |
| Universitas | Universitas Pancasila |
| Mata Kuliah | Pemrograman Berbasis Web (PBW) |
| Praktikum | Pertemuan 3 |

## 📋 Daftar Isi

- [Tentang Proyek](#-tentang-proyek)
- [Tujuan Praktikum](#-tujuan-praktikum)
- [Fitur Website](#-fitur-website)
- [Halaman Aplikasi](#-halaman-aplikasi)
- [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [Arsitektur Aplikasi](#-arsitektur-aplikasi)
- [Struktur Folder](#-struktur-folder)
- [Persyaratan Sistem](#-persyaratan-sistem)
- [Instalasi dan Konfigurasi](#-instalasi-dan-konfigurasi)
- [Menjalankan Aplikasi](#-menjalankan-aplikasi)
- [Panduan Penggunaan](#-panduan-penggunaan)
- [Skenario Pengujian](#-skenario-pengujian)
- [Penanganan Masalah](#-penanganan-masalah)
- [Rencana Pengembangan](#-rencana-pengembangan)
- [Kesimpulan](#-kesimpulan)

## 🎯 Tentang Proyek

LaraPress merupakan proyek website informasi sederhana yang dikembangkan menggunakan framework Laravel dan bahasa pemrograman PHP. Proyek ini menjadi sarana untuk mempelajari dasar pengembangan website dengan framework, mulai dari pengaturan alamat halaman, penyusunan tampilan, hingga menjalankan aplikasi melalui server lokal.

Website memiliki tiga halaman informasi utama, yaitu Home, Tentang Kami, dan Kontak. Setiap halaman mempunyai tujuan penyajian informasi yang berbeda dan dapat diakses melalui navigasi website.

Laravel digunakan untuk mengatur alur permintaan halaman, sedangkan Blade Template membantu menyusun konten HTML yang ditampilkan kepada pengguna.

## 🎓 Tujuan Praktikum

Praktikum ini bertujuan untuk memahami penerapan framework Laravel dalam pengembangan website.

Tujuan pembelajaran meliputi:

1. Mengenal struktur direktori proyek Laravel.
2. Memahami pengaturan routing menggunakan `routes/web.php`.
3. Menggunakan Blade Template untuk membuat tampilan halaman.
4. Memahami hubungan antara URL, routing, dan view.
5. Menyusun halaman website dengan HTML dan CSS.
6. Mengenal penggunaan Composer untuk dependensi PHP.
7. Memahami peran Node.js, npm, dan Vite dalam pengelolaan aset frontend.
8. Menjalankan aplikasi melalui server pengembangan Laravel.
9. Melakukan pemeriksaan dasar terhadap halaman dan navigasi website.

## ✨ Fitur Website

LaraPress dirancang sebagai website informasi dengan beberapa fitur dasar.

| Fitur | Deskripsi |
|---|---|
| 🏠 Halaman Home | Menampilkan informasi pembuka dan pengenalan website. |
| ℹ️ Halaman Tentang Kami | Menyediakan penjelasan mengenai website. |
| 📞 Halaman Kontak | Menampilkan informasi kontak yang tersedia. |
| 🧭 Navigasi Halaman | Menghubungkan halaman melalui menu navigasi. |
| 🎨 Antarmuka Website | Menyajikan konten melalui tata letak HTML dan CSS. |
| 🔗 Routing Laravel | Mengatur alamat URL yang digunakan untuk membuka halaman. |
| 🧩 Blade Template | Menyusun tampilan halaman melalui sistem template Laravel. |

**Catatan:** fitur di atas mengikuti deskripsi repository referensi. Sesuaikan dengan implementasi yang benar-benar ada pada kode proyekmu.

## 🌐 Halaman Aplikasi

### 1. Home

Halaman Home merupakan halaman utama yang menjadi titik awal ketika pengunjung membuka website.

Halaman ini digunakan untuk menampilkan sambutan dan informasi pengantar mengenai LaraPress.

**Tujuan halaman:**
- Memperkenalkan website kepada pengunjung.
- Menampilkan informasi utama.
- Menyediakan akses ke halaman lain melalui navigasi.

### 2. Tentang Kami

Halaman Tentang Kami berfungsi untuk memberikan informasi mengenai website dan penjelasan pendukung yang ingin disampaikan kepada pengunjung.

**Tujuan halaman:**
- Menyajikan informasi mengenai website.
- Memberikan gambaran tentang isi dan tujuan website.
- Menyediakan halaman informasi yang terpisah dari halaman utama.

### 3. Kontak

Halaman Kontak digunakan untuk menampilkan informasi kontak yang tersedia pada website.

**Tujuan halaman:**
- Menampilkan informasi kontak.
- Memudahkan pengunjung menemukan informasi komunikasi yang disediakan.
- Memisahkan informasi kontak dari halaman utama.

## 🛠️ Teknologi yang Digunakan

### Backend

- **PHP 8.2+** — Bahasa pemrograman yang digunakan untuk menjalankan logika aplikasi.
- **Laravel 12** — Framework PHP untuk membangun aplikasi web.
- **Laravel Routing** — Mengatur alamat URL dan menentukan halaman yang ditampilkan.
- **Blade Template** — Template engine Laravel untuk menyusun tampilan halaman.

### Frontend

- **HTML5** — Menyusun struktur konten website.
- **CSS3** — Mengatur warna, tata letak, jarak, dan tampilan elemen halaman.
- **JavaScript** — Dapat digunakan untuk menambahkan interaksi pada sisi browser apabila diterapkan dalam proyek.

### Database

- **MySQL** — Dapat digunakan sebagai database relasional melalui konfigurasi Laravel apabila diperlukan oleh proyek.

Halaman informasi pada praktikum ini tidak otomatis memerlukan database. Penggunaan MySQL untuk menyimpan konten baru diperlukan apabila fungsi tersebut memang diimplementasikan.

### Development Tools

- **Composer** — Mengelola dependensi PHP.
- **Node.js dan npm** — Mendukung pengelolaan paket frontend.
- **Vite** — Mengelola proses pengembangan dan build aset frontend.
- **PHP Artisan** — Menyediakan perintah CLI untuk menjalankan dan mengelola aplikasi Laravel.
- **Git dan GitHub** — Digunakan untuk pengelolaan versi kode dan dokumentasi proyek.

## 🏗️ Arsitektur Aplikasi

Secara umum, proses menampilkan halaman pada aplikasi Laravel dapat digambarkan sebagai berikut:

```text
Pengguna membuka URL
         |
         v
   Browser mengirim
    HTTP Request
         |
         v
    routes/web.php
         |
         v
  Routing menentukan
    halaman tujuan
         |
         v
   Blade View diproses
         |
         v
   HTML dikirim ke
      browser
         |
         v
  Halaman ditampilkan
```

Alur tersebut menjelaskan mekanisme umum Laravel untuk halaman yang langsung menggunakan view. Jika aplikasi menggunakan controller, alur dapat melewati controller sebelum view ditampilkan.

### Peran Komponen

| Komponen | Tanggung Jawab |
|---|---|
| `routes/web.php` | Mendefinisikan rute halaman website. |
| Controller | Menangani logika permintaan apabila digunakan. |
| Blade View | Menyusun tampilan halaman. |
| `public/` | Menyediakan titik masuk aplikasi dan aset publik. |
| `resources/` | Menyimpan sumber daya tampilan dan aset frontend. |
| `config/` | Menyimpan konfigurasi aplikasi, termasuk database. |

## 📂 Struktur Folder

Berikut contoh struktur utama proyek Laravel yang dapat digunakan sebagai acuan. Struktur aktual harus mengikuti isi folder `LaraPress` milikmu.

```text
LaraPress/
├── app/
│   ├── Http/
│   │   └── Controllers/
│   ├── Models/
│   └── Providers/
├── bootstrap/
├── config/
│   └── database.php
├── database/
│   ├── factories/
│   ├── migrations/
│   └── seeders/
├── public/
├── resources/
│   ├── css/
│   ├── js/
│   └── views/
│       ├── welcome.blade.php
│       ├── about.blade.php
│       └── kontak.blade.php
├── routes/
│   ├── console.php
│   └── web.php
├── tests/
├── .env.example
├── artisan
├── composer.json
├── package.json
└── vite.config.js
```

### Keterangan Direktori

- `app/` — Menyimpan komponen utama aplikasi.
- `app/Http/Controllers/` — Tempat controller apabila digunakan.
- `app/Models/` — Menyimpan model untuk representasi data.
- `bootstrap/` — Menyediakan komponen bootstrap aplikasi Laravel.
- `config/` — Menyimpan pengaturan aplikasi.
- `database/` — Berisi migrasi, factory, dan seeder database.
- `public/` — Menyediakan titik masuk web dan aset publik.
- `resources/views/` — Menyimpan file Blade Template.
- `resources/css/` — Menyimpan sumber stylesheet.
- `resources/js/` — Menyimpan sumber JavaScript.
- `routes/web.php` — Mengatur routing untuk halaman web.
- `tests/` — Menyimpan file pengujian otomatis.
- `composer.json` — Mendefinisikan dependensi dan konfigurasi Composer.
- `package.json` — Mendefinisikan paket serta perintah frontend.
- `vite.config.js` — Mengatur proses build aset menggunakan Vite.

Nama file view di atas merupakan contoh dari repository referensi. Periksa direktori `resources/views/` untuk memastikan nama file sebenarnya.

## 💻 Persyaratan Sistem

Sebelum menjalankan proyek, pastikan perangkat memiliki:

- PHP versi yang kompatibel dengan Laravel 12, umumnya PHP 8.2 atau lebih baru.
- Composer.
- Node.js dan npm.
- Browser modern.
- Git jika ingin melakukan clone repository.

MySQL diperlukan apabila proyek dikonfigurasi untuk menggunakan database MySQL. XAMPP atau Laragon dapat digunakan untuk menyediakan lingkungan server lokal dan MySQL.

Periksa instalasi melalui terminal:

```bash
php -v
composer -V
node -v
npm -v
git --version
```

Jika seluruh perintah dapat dijalankan dan menampilkan versi perangkat lunak, lanjutkan ke proses instalasi.

## 🚀 Instalasi dan Konfigurasi

### 1. Clone Repository

Ganti URL di bawah dengan URL repository GitHub milikmu.

```bash
git clone URL_REPOSITORY_MILIKMU
```

Masuk ke folder repository yang telah diunduh. Jika file Laravel berada dalam subfolder `LaraPress`, masuk ke folder tersebut:

```bash
cd NAMA_REPOSITORY/LaraPress
```

Sesuaikan perintah dengan struktur folder aktual. Jika `composer.json` berada langsung di root repository, tidak perlu masuk ke subfolder `LaraPress`.

### 2. Install Dependensi PHP

Jalankan:

```bash
composer install
```

Perintah tersebut memasang dependensi PHP berdasarkan konfigurasi Composer proyek.

### 3. Install Dependensi Frontend

Jalankan:

```bash
npm install
```

Proses ini memasang paket frontend yang diperlukan oleh proyek.

### 4. Menyiapkan File Environment

Salin `.env.example` menjadi `.env`.

Untuk Windows PowerShell:

```powershell
Copy-Item .env.example .env
```

Untuk Command Prompt:

```cmd
copy .env.example .env
```

Kemudian buat application key:

```bash
php artisan key:generate
```

File `.env` digunakan untuk menyimpan pengaturan lingkungan aplikasi. Jangan mengunggah file `.env` yang berisi kredensial pribadi ke repository publik.

### 5. Konfigurasi Database

Jika proyek menggunakan MySQL, buat database terlebih dahulu melalui phpMyAdmin atau terminal MySQL.

Contoh pembuatan database:

```sql
CREATE DATABASE larapress;
```

Sesuaikan pengaturan database dalam file `.env`:

```dotenv
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=larapress
DB_USERNAME=root
DB_PASSWORD=
```

Nilai tersebut merupakan contoh untuk lingkungan lokal. Sesuaikan username, password, nama database, dan port dengan konfigurasi perangkatmu.

Jika proyek tidak membutuhkan database untuk halaman informasi, konfigurasi MySQL dan migrasi dapat dilewati sesuai kebutuhan aplikasi.

### 6. Menjalankan Migrasi

Jika proyek menggunakan database dan memiliki migrasi yang diperlukan, jalankan:

```bash
php artisan migrate
```

Untuk melihat status migrasi:

```bash
php artisan migrate:status
```

Jalankan migrasi hanya setelah koneksi database dikonfigurasi dengan benar. Migrasi akan membuat struktur tabel yang didefinisikan oleh file migrasi proyek.

### 7. Menjalankan Vite

Untuk mode pengembangan frontend:

```bash
npm run dev
```

Untuk membuat aset produksi:

```bash
npm run build
```

Gunakan perintah yang sesuai dengan kebutuhan. Proses Vite hanya diperlukan jika proyek menggunakan konfigurasi aset frontend tersebut.

## ▶️ Menjalankan Aplikasi

Pastikan dependensi sudah terpasang dan konfigurasi lingkungan sudah sesuai.

Jalankan server Laravel:

```bash
php artisan serve
```

Buka browser dan akses:

**http://127.0.0.1:8000**

Jika halaman tidak dapat dibuka, pastikan server Laravel berjalan dan periksa pesan kesalahan pada terminal.

Apabila aset frontend menggunakan Vite dalam mode pengembangan, jalankan `npm run dev` pada terminal terpisah.

## 📖 Panduan Penggunaan

### Membuka Halaman Home

1. Jalankan aplikasi.
2. Buka alamat utama website.
3. Periksa apakah halaman pembuka ditampilkan dengan benar.
4. Periksa tata letak, teks, dan elemen visual.

### Membuka Halaman Tentang Kami

1. Gunakan menu navigasi website.
2. Pilih halaman Tentang Kami.
3. Pastikan informasi yang tersedia dapat dibaca dan halaman berhasil dimuat.

### Membuka Halaman Kontak

1. Gunakan menu navigasi.
2. Pilih halaman Kontak.
3. Periksa informasi kontak yang ditampilkan.

### Berpindah Antarhalaman

Navigasi digunakan untuk mempermudah pengunjung mengakses halaman yang berbeda. Alamat URL setiap halaman harus sesuai dengan rute yang didefinisikan dalam `routes/web.php`.

## 🧪 Skenario Pengujian

Pengujian berikut dapat dilakukan setelah aplikasi dijalankan.

| No. | Skenario | Hasil yang Diharapkan |
|---|---|---|
| 1 | Membuka URL utama | Halaman Home tampil. |
| 2 | Membuka halaman Tentang Kami | Halaman informasi dapat diakses. |
| 3 | Membuka halaman Kontak | Halaman kontak dapat diakses. |
| 4 | Menggunakan menu navigasi | Pengunjung dapat berpindah halaman. |
| 5 | Memuat ulang halaman | Halaman dapat dimuat kembali. |
| 6 | Membuka URL yang tidak terdaftar | Laravel menampilkan respons halaman tidak ditemukan. |
| 7 | Menjalankan proses build aset | Vite menyelesaikan build jika dikonfigurasi. |
| 8 | Menjalankan pengujian Laravel | Hasil pengujian ditampilkan oleh sistem. |

Tabel ini merupakan daftar skenario pengujian yang disarankan. Status berhasil atau gagal perlu ditentukan berdasarkan pengujian yang benar-benar dijalankan.

### Pengujian Otomatis

Laravel menyediakan fasilitas pengujian otomatis. Untuk menjalankan pengujian yang tersedia pada proyek, gunakan:

```bash
php artisan test
```

Periksa hasil keluaran terminal untuk mengetahui jumlah pengujian yang berhasil dan gagal.

## 🛠️ Penanganan Masalah

### Composer Tidak Dikenali

Pastikan Composer telah terpasang dan tersedia pada PATH sistem. Tutup lalu buka kembali terminal setelah memperbarui konfigurasi PATH.

### Perintah `php artisan` Gagal

Periksa apakah terminal berada di direktori yang berisi file `artisan`. Pastikan pula dependensi Composer telah terpasang.

### File `.env` Tidak Ditemukan

Salin `.env.example` menjadi `.env`, lalu jalankan:

```bash
php artisan key:generate
```

Pastikan file dibuat di direktori proyek Laravel yang benar.

### Database Tidak Dapat Terhubung

Periksa status layanan MySQL dan pastikan nilai `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME`, serta `DB_PASSWORD` sesuai dengan konfigurasi lokal.

### Halaman Tidak Dapat Dibuka

Pastikan server Laravel berjalan, alamat URL benar, dan rute halaman sudah terdaftar dalam `routes/web.php`.

### Tampilan CSS Tidak Muncul

Jika proyek menggunakan Vite, pastikan dependensi frontend telah dipasang dan jalankan:

```bash
npm run dev
```

Jika ingin menyiapkan aset produksi, gunakan `npm run build` sesuai konfigurasi proyek.

## 🔧 Rencana Pengembangan

LaraPress dapat dikembangkan lebih lanjut sesuai kebutuhan dan materi praktikum berikutnya.

### Pengembangan Fungsionalitas

- Menambahkan formulir kontak yang memvalidasi input pengguna.
- Menyimpan pesan pengunjung ke database apabila diperlukan.
- Membuat halaman administrasi untuk mengelola informasi.
- Menambahkan operasi CRUD pada data yang dikelola.
- Menambahkan validasi formulir di sisi server.

### Pengembangan Antarmuka

- Menggunakan layout Blade bersama untuk navigasi dan footer.
- Menambahkan komponen tampilan yang dapat digunakan kembali.
- Meningkatkan responsivitas halaman pada berbagai ukuran layar.
- Memperbaiki konsistensi warna, tipografi, dan jarak elemen.

### Pengembangan Kualitas Kode

- Menambahkan pengujian otomatis untuk setiap halaman.
- Memperbaiki penanganan halaman yang tidak ditemukan.
- Memisahkan logika aplikasi dan tampilan.
- Menambahkan dokumentasi untuk setiap fitur baru.

Daftar tersebut merupakan rencana pengembangan, bukan pernyataan bahwa semua fitur sudah tersedia.

## 📌 Kesimpulan

Praktikum 3 memperkenalkan penggunaan Laravel untuk membangun website informasi dengan beberapa halaman yang saling terhubung. Melalui LaraPress, konsep routing, Blade Template, struktur direktori Laravel, pengelolaan aset frontend, dan server pengembangan dapat dipelajari dalam sebuah proyek sederhana.

Dokumentasi ini menjelaskan tujuan aplikasi, komponen utama, langkah instalasi, cara menjalankan website, dan skenario pengujian. Pemahaman terhadap konsep tersebut dapat menjadi dasar untuk mengembangkan aplikasi web dengan fungsi yang lebih kompleks pada praktikum berikutnya.

---

<p align="center">
  <b>Praktikum 3 — Pemrograman Berbasis Web</b><br>
  Ridwan Odi Nugroho · 4524210089<br>
  Universitas Pancasila
</p>
