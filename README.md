# Laporan Praktikum Pemweb Modul 1
## Anggota

| Nama | NRP |
| :--- | :--- |
| Irsa Fairuza | 5027251115 |
| Wildan Alfarezy | 5027251088 |
| Dafa Rido | 5027251129 |

## Penjelasan
1. Deskripsi Proyek
Proyek ini adalah pengembangan website portofolio dan Curriculum Vitae (CV) interaktif untuk tokoh publik (Bahlil Lahadalia). Website ini dibangun sepenuhnya dari awal (native from scratch) menggunakan murni HTML5 dan CSS3, tanpa menggunakan framework eksternal seperti Bootstrap atau Tailwind, guna memenuhi standar tugas praktikum Pemrograman Web.

2. Struktur Halaman
Website ini terdiri dari dua halaman utama yang saling terhubung:

Halaman Beranda (index.html): Berfungsi sebagai Landing Page yang menyambut pengunjung. Halaman ini memuat Hero Section, deskripsi singkat, highlight keahlian, dan formulir kontak yang interaktif.

Halaman CV (cv.html): Berfungsi sebagai halaman detail yang menyajikan tata letak ala dokumen riwayat hidup. Halaman ini memuat foto profil, riwayat pendidikan, dan rekam jejak karir yang divisualisasikan menggunakan desain timeline vertikal.

3. Penerapan Teknis HTML & CSS
Untuk memenuhi syarat fungsionalitas dan estetika, website ini menerapkan beberapa teknik CSS modern:

Tata Letak (Layouting): Proyek ini secara intensif mengkombinasikan Flexbox (digunakan untuk merapikan posisi Navbar, menyusun daftar keahlian, dan menengahkan elemen ikon) serta CSS Grid (digunakan sebagai fondasi utama halaman CV untuk membelah layar menjadi dua kolom kiri dan kanan yang proporsional).

Interaktivitas & Posisi: Menerapkan pseudo-class seperti :hover pada tombol CTA (Call to Action) dan ikon media sosial untuk memberikan umpan balik visual (seperti perubahan warna latar dan pembesaran ukuran) saat disentuh kursor. Selain itu, penggunaan position: sticky diterapkan agar elemen tertentu tetap menempel di layar saat halaman digulir ke bawah.

Desain Responsif (Mobile-Friendly): Menerapkan aturan Media Queries (@media screen and (max-width: 768px)). Hal ini memastikan bahwa tata letak yang awalnya memiliki banyak kolom di layar laptop, akan secara otomatis menyusut dan menumpuk menjadi satu kolom (berbaris ke bawah) saat dibuka melalui layar smartphone.

4. Kolaborasi & Version Control
Pengembangan proyek ini dilakukan secara kolaboratif bersama anggota tim menggunakan sistem version control Git. Proses integrasi kode, pembagian tugas (seperti pengerjaan halaman utama dan halaman CV), serta finalisasi proyek dikelola secara terpusat melalui repositori GitHub publik.
