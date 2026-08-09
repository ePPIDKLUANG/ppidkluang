# 🏛️ Pengurusan Sistem Maklumat PPID Kluang

Sistem Maklumat Perkhidmatan Pemohonan Informasi dan Dokumentasi (PPID) Daerah Kluang. Sistem ini dibangunkan untuk mengurus, menyimpan, dan memproses permohonan maklumat daripada orang awam secara digital, cekap, dan telus.

## 🚀 Ciri-Ciri Utama
* **Pendaftaran Permohonan:** Borang digital untuk orang awam memohon maklumat.
* **Semakan Status:** Pemohon boleh menyemak status permohonan secara masa nyata.
* **Dashboard Pentadbir:** Panel kawalan untuk pegawai PPID meluluskan atau menolak permohonan.
* **Laporan & Statistik:** Penjanaan graf dan laporan bulanan/tahunan permohonan.
* **Notifikasi Emel:** Makluman automatik kepada pemohon apabila status dikemas kini.

## 🛠️ Teknologi Yang Digunakan
* **Frontend:** HTML5, CSS3, JavaScript (atau Bootstrap / Tailwind CSS / React)
* **Backend:** PHP (Laravel) / Node.js / Python (Django)
* **Pangkalan Data:** MySQL / PostgreSQL
* **Pelayan:** Apache / Nginx

## 📋 Keperluan Sistem
Sebelum memulakan, pastikan perisian berikut telah dipasang pada komputer anda:
* PHP >= 8.x (atau versi teknologi pilihan anda)
* Composer
* MySQL Server
* Git

## ⚙️ Cara Pemasangan

1. **Klon repositori ini:**
   ```bash
   git clone https://github.com
   ```

2. **Masuk ke dalam direktori projek:**
   ```bash
   cd ppid-kluang
   ```

3. **Pasang komponen yang diperlukan (dependencies):**
   ```bash
   composer install
   npm install
   ```

4. **Sediakan fail konfigurasi persekitaran:**
   Salin fail `.env.example` kepada `.env` dan kemas kini maklumat pangkalan data anda.
   ```bash
   cp .env.example .env
   ```

5. **Jana kunci aplikasi (jika guna Laravel):**
   ```bash
   php artisan key:generate
   ```

6. **Laksanakan migrasi pangkalan data:**
   ```bash
   php artisan migrate --seed
   ```

7. **Jalankan pelayan tempatan:**
   ```bash
   php artisan serve
   ```
   Buka `http://localhost:8000` pada pelayar web anda.

## 👤 Peranan Pengguna (Roles)
1. **Orang Awam (Pemohon):** Mengisi borang dan menyemak status.
2. **Pegawai PPID (Pentadbir):** Memproses permohonan dan mengemas kini status.
3. **Pengurusan Tertinggi:** Melihat laporan dan statistik keseluruhan.

## 🔒 Lesen
Projek ini dilesenkan di bawah Lesen MIT - lihat fail [LICENSE](LICENSE) untuk maklumat lanjut.

## 📞 Hubungi
Untuk sebarang pertanyaan atau laporan pepijat (bugs), sila hubungi:
* **Nama:** Unit ICT PPID Kluang
* **Emel:** ict.ppidkluang@email.com
* **Laman Web:** [Situs Rasmi PPID Kluang](#)
