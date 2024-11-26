# 🎬 Movie Catalogue - Progressive Web Apps (PWAs)

## 📝 Gambaran Proyek

Movie Catalogue adalah Aplikasi Web Progresif (Progressive Web App / PWA) yang dirancang untuk memberikan pengalaman pengguna yang mulus dalam menjelajahi katalog film. Dibangun dengan teknologi web modern, aplikasi ini menawarkan kemampuan offline, performa cepat, dan desain responsif.

## 🔧 Komponen PWA

### Komponen Wajib PWA

#### 1. Application Shell

- Kerangka antarmuka aplikasi yang disimpan dalam cache
- Komponen statis seperti header, sidebar, footer
- Memungkinkan tampilan instan saat aplikasi dibuka

#### 2. Web App Manifest (`manifest.json`)

- File JSON sederhana untuk mengontrol tampilan aplikasi
- Mendefinisikan ikon, nama, dan perilaku aplikasi
- Memungkinkan "instalasi" di layar utama perangkat

#### 3. Service Worker

- Script JavaScript yang berjalan di latar belakang
- Mengelola caching dan kemampuan offline
- Mengontrol request jaringan
- Memungkinkan pengalaman pengguna tanpa koneksi internet

#### 4. Cache API

- Penyimpanan lokal untuk resource aplikasi
- Menyimpan file dan data untuk akses cepat
- Berbeda dengan browser cache bawaan
- Dapat dikelola secara manual melalui service worker

#### 5. Fetch API

- Interface standar untuk melakukan request
- Digunakan untuk berinteraksi dengan service worker
- Memungkinkan evaluasi dan pengarahan request ke Cache API

### Komponen Opsional PWA

#### 6. IndexedDB

- Sistem penyimpanan lokal berbasis NoSQL
- Menyimpan objek JavaScript
- Berguna untuk caching dan penyimpanan data kompleks

#### 7. Web Socket

- Standar komunikasi real-time
- Mendukung fitur seperti chat, berita, game online

#### 8. Notifications

- Menampilkan pesan popup
- Mengajak pengguna kembali ke aplikasi
- Memberikan informasi dan update

## ✨ Fitur Utama

### Kemampuan Progressive Web App

- 🌐 **Responsif Penuh**: Berfungsi sempurna di desktop, mobile, dan tablet
- 🔒 **Aman**: Berjalan pada HTTPS untuk keamanan tingkat lanjut
- 📲 **Dapat Dipasang**: Bisa ditambahkan ke layar utama seperti aplikasi native
- 🌍 **Dukungan Offline**: Beroperasi bahkan dengan koneksi internet buruk
- 🔔 **Notifikasi Push**: Mengajak kembali pengguna dengan pembaruan real-time

### Fitur Spesifik Katalog Film

- 🎥 Jelajahi koleksi film
- 🔍 Fungsi pencarian
- ⭐ Detail film dan rating
- 💾 Caching data film offline

## 🛠 Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript
- IndexedDB
- Fetch API
- Web Socket (opsional)

## 🚀 Memulai

### Prasyarat

- Browser modern (Chrome, Firefox, Edge)
- Node.js
- npm

### Instalasi

1. Clone repositori

   ```bash
   git clone https://github.com/username/movie-catalogue.git
   ```

2. Masuk direktori proyek

   ```bash
   cd movie-catalogue
   ```

3. Instal dependensi

   ```bash
   npm install
   ```

4. Jalankan aplikasi
   ```bash
   npm start
   ```

## 🔍 Arsitektur

- **Rendering**: Client-Side Rendering (CSR)
- **Struktur**: Single Page Application (SPA)
- **Tujuan**: Pengalaman pengguna mirip aplikasi native

## 🌟 Keunggulan PWA

- Tidak membutuhkan toko aplikasi
- Update otomatis saat refresh
- Mudah dipublikasi dan dibagikan
- Lebih sedikit penggunaan data
- Performa cepat

## ⚠️ Batasan

- Dukungan terbatas pada browser modern
- Beberapa fitur native belum sepenuhnya tersedia

## 🤝 Kontribusi

1. Fork repositori
2. Buat cabang fitur (`git checkout -b fitur/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Tambahkan fitur luar biasa'`)
4. Push ke cabang (`git push origin fitur/AmazingFeature`)
5. Buka Pull Request

## 📄 Lisensi

Didistribusikan di bawah Lisensi MIT.

## 🚦 Status Proyek

🟢 Pengembangan Aktif

## 📞 Kontak

[Aditya Pratama] - [aditypraa@gmail.com]

Tautan Proyek: [https://github.com/Aditypraa/movie-catalogue](https://github.com/Aditypraa/movie-catalogue)
