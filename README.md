# Himpunan Mahasiswa Fisika Teknik ITB Web Application

## Deskripsi Project

**Himpunan Mahasiswa Fisika Teknik ITB** adalah website resmi yang bertujuan menjadi pusat informasi, komunikasi, dan koordinasi kegiatan bagi mahasiswa Fisika Teknik di Institut Teknologi Bandung (ITB). Website ini didesain untuk mempermudah penyebaran pengumuman, pengelolaan acara, serta interaksi antar anggota himpunan dalam lingkungan kampus.

Dibangun menggunakan **Next.js** untuk pengalaman frontend yang cepat, responsif, dan SEO-friendly, serta didukung backend dan infrastruktur modern menggunakan **Docker** untuk kemudahan deployment, **GitHub** untuk manajemen kode dan automatisasi, **Nginx** sebagai reverse proxy yang mengatur trafik, **Cloudflare CDN** untuk distribusi konten cepat dan keamanan, serta **PostgreSQL** sebagai penyimpan data yang aman dan scalable.

## Arsitektur dan Teknologi

- **Next.js**: Framework React dengan kemampuan SSR dan SSG untuk performa dan pengindeksan mesin pencari yang optimal.
- **Docker**: Penggunaan container guna memastikan konsistensi environment pengembangan dan produksi.
- **GitHub**: Platform version control dan continuous integration/deployment (CI/CD).
- **Nginx**: Reverse proxy yang mengelola permintaan, SSL termination, dan caching.
- **Cloudflare CDN**: Mempercepat akses global dan melindungi situs dari serangan siber.
- **PostgreSQL**: Basis data relasional untuk menyimpan data anggota, pengumuman, kegiatan, dan lain-lain.

## Fitur Utama

1. **Beranda Informatif**  
   Menampilkan berita terbaru, pengumuman penting, dan highlight kegiatan seputar Himpunan Fisika Teknik ITB.

2. **Profil Himpunan**  
   Informasi tentang sejarah, visi & misi, struktur organisasi, serta kontak resmi himpunan.

3. **Pengumuman Resmi**  
   Sistem untuk mengelola dan mempublikasikan pengumuman resmi himpunan yang dapat diakses oleh seluruh anggota.

4. **Kalender Kegiatan & Event**  
   Pemantauan jadwal seminar, workshop, lomba, dan acara kampus khusus untuk mahasiswa Fisika Teknik.

5. **Forum Diskusi Mahasiswa**  
   Media interaktif untuk bertukar pikiran, bertanya, dan berbagi informasi antar mahasiswa.

6. **Manajemen Anggota**  
   Registrasi anggota baru, pengelolaan hak akses anggota (anggota biasa, pengurus, admin), serta database anggota yang terintegrasi.

7. **Dokumentasi dan Arsip**  
   Penyimpanan digital dokumen penting seperti notulen rapat, materi kegiatan, dan laporan keuangan.

## Cara Menjalankan Project

Langkah-langkah untuk setup dan menjalankan project akan meliputi:

1. Clone repository dari GitHub.
2. Setup environment menggunakan Docker container sesuai konfigurasi yang ada.
3. Konfigurasi Nginx sebagai reverse proxy dengan SSL dan caching.
4. Integrasi dengan Cloudflare CDN untuk akselerasi dan proteksi.
5. Jalankan database PostgreSQL dengan konfigurasi yang aman.
6. Build dan deploy aplikasi Next.js menggunakan pipeline CI/CD di GitHub.

Dokumentasi lengkap setup dan deployment tersedia di folder `/docs`.

---

Dengan struktur dan fitur unggulan tersebut, website ini akan menjadi platform efektif yang mendukung komunikasi, transparansi, dan kolaborasi dalam himpunan mahasiswa Fisika Teknik ITB.

---

*Terima kasih telah menggunakan proyek ini! Jangan ragu untuk membuka isu atau mengajukan kontribusi via GitHub.*

