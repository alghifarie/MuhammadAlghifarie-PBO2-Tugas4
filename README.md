# MuhammadAlghifarie-PBO2-Tugas4
Berikut adalah file README untuk program **PerhitunganHari** Anda:

```markdown
# Aplikasi Perhitungan Hari

**Aplikasi Perhitungan Hari** adalah program berbasis Java dengan GUI yang membantu pengguna menentukan jumlah hari dalam suatu bulan tertentu berdasarkan tahun yang dipilih. Aplikasi ini juga mendukung pemilihan tanggal menggunakan kalender.

## Fitur

- **Hitung Jumlah Hari**:
  - Hitung jumlah hari dalam bulan tertentu pada tahun tertentu.
  - Menampilkan hasil di layar aplikasi.
- **Dukungan Kalender**:
  - Pilih tanggal langsung dari kalender interaktif.
- **Reset Input**:
  - Tombol **Ulang** mengatur ulang semua input ke kondisi awal.
- **Keluar dari Aplikasi**:
  - Tombol **Keluar** untuk menutup aplikasi dengan mudah.

## Cara Menggunakan

1. Jalankan aplikasi.
2. Pilih bulan dari dropdown menu.
3. Masukkan tahun menggunakan spinner.
4. Alternatif: Pilih tanggal langsung dari kalender.
5. Klik tombol **Hitung Hari** untuk melihat jumlah hari dalam bulan yang dipilih.
6. Klik tombol **Ulang** untuk mengatur ulang input.
7. Klik tombol **Keluar** untuk menutup aplikasi.

## Persyaratan Sistem

- **Java Development Kit (JDK)** versi 8 atau lebih baru.
- **Swing Library** (bagian dari Java Standard Edition).
- **Toedter Calendar Library** untuk fitur kalender interaktif.

## Instalasi dan Menjalankan Aplikasi

1. Pastikan JDK telah diinstal di komputer Anda.
2. Clone repositori ini atau salin file program ke direktori lokal Anda:
   ```bash
   git clone https://github.com/username/PerhitunganHari.git
   ```
3. Pastikan library *Toedter Calendar* tersedia dan ditambahkan ke project Anda.
4. Compile program menggunakan perintah:
   ```bash
   javac -cp .:toedter-calendar.jar PerhitunganHari.java
   ```
5. Jalankan aplikasi dengan perintah:
   ```bash
   java -cp .:toedter-calendar.jar PerhitunganHari
   ```

