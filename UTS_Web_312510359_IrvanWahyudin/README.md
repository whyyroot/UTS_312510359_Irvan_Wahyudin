

# Website Portofolio & Profil Pribadi - Irvan Wahyudin

Project website profil pribadi responsif yang dibuat menggunakan **HTML5** dan **CSS3**. Website ini menyajikan informasi riwayat pendidikan, pengalaman kerja, daftar keahlian di bidang Teknik Informatika dan Keamanan Siber, media interaktif, serta formulir kontak.

Project ini disusun sebagai bagian dari penyelesaian **Tugas UTS Pemrograman Web**.

---

## 👤 Profil Pembuat

**Irvan Wahyudin – 312510359**
- **Institusi**: S1 Teknik Informatika – Universitas Pelita Bangsa
- **Peran / Pekerjaan**: Mahasiswa | Assistant Chief of Store | Junior Network Engineering
- **Minat Utama**: Cyber Security, Administrasi Sistem & Jaringan (Linux, OpenWrt, MikroTik, STB Server Setup).

---

## 📌 Fitur Utama

- **Header & Navigasi Sticky**: Navigasi yang memudah pengaksesan antar-bagian (*section*) pada halaman.
- **Hero Panel**: Area tampilan utama yang menyambut pengunjung secara visual.
- **Biografi & Profil Utama**: Ringkasan latar belakang, domisili, dan minat karier teknis.
- **Tabel Riwayat Pendidikan**: Catatan jejak akademis serta pelatihan/bootcamp.
- **Tabel Pengalaman Kerja**: Rincian riwayat pekerjaan beserta uraian tugas operasional.
- **Daftar Keahlian (*Skills*)**: Pemetaan kemampuan di bidang *programming*, *system administration*, *cyber security*, dan *hardware*.
- **Multimedia Interaktif**: Integrasi pemutar audio dan video native HTML5.
- **Formulir Kontak**: Form pesan interaktif lengkap dengan validasi bawaan HTML5 (`required`, `type="email"`).
- **Desain Responsif**: Tampilan yang menyesuaikan dengan berbagai ukuran layar (*desktop* dan *mobile*).

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Menggunakan tag semantik seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<video>`, `<audio>`, dan `<footer>`.
- **CSS3**: Menggunakan teknik layouting modern (*Flexbox*, *Media Queries* untuk responsivitas, dan visual effect).

---

## 📁 Struktur Folder

```text
.
├── index.html       # Berkas utama struktur halaman web
├── style.css        # Berkas gaya styling CSS
├── images/          # Direktori penyimpanan gambar
│   └── profil.jpg   # Foto profil utama
├── media/           # Direktori aset audio & video
│   ├── audio.mp3    # Berkas audio perkenalan
│   └── video.mp4    # Berkas video portofolio
└── README.md        # Dokumentasi proyek
```
---

## 📝 Laporan Ringkas Proses Pembuatan

Proses pengerjaan website ini dibagi menjadi beberapa tahapan utama:

### 1. Perencanaan & Struktur HTML (`index.html`)
* **Penyusunan Struktur Semantik**: Menentukan hirarki dokumen agar mudah dibaca oleh peramban dan penyedia mesin pencari.
* **Pengelompokan Komponen**: Membagi halaman menjadi beberapa bagian utama (`#hero`, `#biografi`, `#pendidikan`, `#pengalaman`, `#keahlian`, `#multimedia`, `#kontak`).
* **Pembuatan Tabel & Form**: Menyusun tabel data riwayat dan menyiapkan form kontak dengan atribut pengujian input bawaan.

### 2. Penataan Gaya & Layouting CSS (`style.css`)
* **Sistem Warna & Tipografi**: Menggunakan palet warna Slate/Blue modern (`#0f172a`, `#0ea5e9`, `#2563eb`) dengan font `Segoe UI`.
* **Layout Flexbox**: Menerapkan Flexbox pada navigasi, kartu profil, pemutar multimedia, dan formulir untuk memastikan tata letak yang konsisten dan rapi.
* **Styling Komponen Interaktif**: Memberikan efek *hover* pada tautan navigasi, tombol kirim, serta fokus input form.

### 3. Pengujian Responsivitas & Media Queries
* **Penerapan Media Query**: Menambahkan pemutus breakpoint `@media (max-width: 768px)` agar tampilan berubah secara dinamis pada layar kecil (navigasi memposisikan ulang item dan kartu profil bertumpuk secara vertikal).

### 4. Pengujian & Evaluasi
* Memastikan seluruh tautan navigasi berjalan dengan baik (*smooth scroll* / *anchor link*).
* Memastikan validasi formulir kontak berfungsi ketika field kosong atau format email tidak sesuai.
* Memastikan elemen audio dan video dapat diputar dengan baik pada berbagai peramban web.

---

## 🖼️ Screenshot Hasil Tampilan

Berikut adalah penampakan antarmuka dari website profil pribadi yang telah dibuat:

### 1. Tampilan Utam & Hero Panel (Desktop)
![Tampilan Hero & Profil](docs/screenshot-hero.png)
*Gambar 1: Tampilan Header Sticky, Hero Panel, dan Biografi Utama.*

### 2. Riwayat Pendidikan & Pengalaman Kerja
![Tampilan Tabel Data](docs/screenshot-tables.png)
*Gambar 2: Tampilan Tabel Riwayat Pendidikan dan Pengalaman Kerja Ritel.*

### 3. Pemutar Multimedia & Form Kontak
![Tampilan Multimedia & Form](docs/screenshot-media-form.png)
*Gambar 3: Tampilan Pemutar Audio/Video serta Formulir Kontak Interaktif.*

### 4. Tampilan Responsif (Mobile)
![Tampilan Mobile](docs/screenshot-mobile.png)
*Gambar 4: Penyesuaian Layout pada Layar Perangkat Seluler (Smartphones).*

---

## 🚀 Mencoba Proyek
<a href="https://tugas.wahyusite.web.id/"><img src="https://img.shields.io/badge/CLICK_IN_HERE-8A2BE2"/></a> for try web me



