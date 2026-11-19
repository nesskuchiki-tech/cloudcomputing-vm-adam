LAPORAN PRAKTIKUM LINUX

Konfigurasi Repository Debian 13 (Trixie) dan Q4OS

Identitas Mahasiswa

- Nama: Adam Maulana
- NIM: 24013002
- Sistem Operasi: Debian GNU/Linux 13 (Trixie)
- Distribusi: Q4OS

1. Tujuan Praktikum

Praktikum ini bertujuan untuk memahami konfigurasi repository pada sistem operasi Linux, khususnya Debian 13 dan Q4OS, serta mengetahui cara mengelola sumber paket menggunakan APT.

2. Dasar Teori

Repository merupakan tempat penyimpanan paket aplikasi Linux yang digunakan untuk mengunduh, memasang, dan memperbarui perangkat lunak.

APT (Advanced Package Tool) adalah sistem manajemen paket yang digunakan Debian untuk mengelola instalasi dan pembaruan aplikasi.

3. Langkah-Langkah Praktikum

A. Mengecek Versi Sistem Operasi

Perintah yang digunakan:

cat /etc/os-release

Hasil menunjukkan bahwa sistem operasi yang digunakan adalah Debian GNU/Linux 13 (Trixie).

B. Mengecek Konfigurasi Repository

Perintah yang digunakan:

cat /etc/apt/sources.list.d/10-q4os.sources

Konfigurasi ini digunakan untuk melihat sumber repository Debian dan Q4OS yang tersedia pada sistem.

C. Repository Debian

Repository Debian digunakan sebagai sumber paket utama sistem operasi, termasuk komponen:

- Main
- Contrib
- Non-free
- Non-free-firmware

D. Repository Q4OS

Repository Q4OS digunakan untuk menyediakan paket tambahan dan pembaruan khusus distribusi Q4OS.

E. Memperbarui Daftar Paket

Perintah yang digunakan:

sudo apt update

Perintah tersebut berfungsi memperbarui daftar paket dari repository yang telah dikonfigurasi.

4. Hasil Praktikum

Berdasarkan praktikum yang dilakukan, sistem operasi berhasil diidentifikasi sebagai Debian GNU/Linux 13 (Trixie). Konfigurasi repository Debian dan Q4OS juga diperiksa melalui terminal.

Hasil keberhasilan pembaruan repository perlu dibuktikan dengan dokumentasi keluaran perintah "sudo apt update".

5. Kesimpulan

Dari praktikum ini dapat disimpulkan bahwa repository memiliki peran penting dalam pengelolaan aplikasi Linux. Dengan menggunakan APT, pengguna dapat memperbarui daftar paket dan menginstal aplikasi dengan lebih mudah. Konfigurasi repository yang benar juga diperlukan agar proses pembaruan berjalan dengan baik.

6. Dokumentasi

Tambahkan screenshot berikut ke repository GitHub:

1. Screenshot pengecekan versi Debian 13.
2. Screenshot konfigurasi repository Debian.
3. Screenshot konfigurasi repository Q4OS.
4. Screenshot hasil menjalankan "sudo apt update".

---

Nama: Adam Maulana
NIM: 24013002
Keterangan: Laporan Praktikum Konfigurasi Repository Linux Debian 13 dan Q4OS.
