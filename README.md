# 🇮🇩 NIK Parser – Ekstrak Informasi dari NIK KTP Indonesia

![Preview](https://via.placeholder.com/800x400/fcfcfd/111111?text=NIK+Parser+Preview)  
*(Ganti dengan screenshot aktual saat deploy)*

Aplikasi web ringan untuk **menerjemahkan 16 digit NIK (Nomor Induk Kependudukan)** KTP Indonesia menjadi informasi terstruktur seperti provinsi, kabupaten/kota, jenis kelamin, tanggal lahir, usia, zodiak, dan lainnya — **langsung di browser, tanpa instalasi**.

> ⚠️ **Catatan Penting**: Data yang dihasilkan hanya berdasarkan struktur resmi NIK. Informasi lokasi mencerminkan **tempat pertama kali NIK dibuat** atau **tempat lahir**, **bukan domisili pemilik saat ini**.

---

## 🔍 Fitur

- ✅ Parsing NIK 16 digit secara real-time
- 🌐 Tampilan **premium minimalist** yang responsif (mobile & desktop)
- 📊 Menampilkan:
  - Provinsi & Kabupaten/Kota
  - Kecamatan & Kode Pos
  - Jenis Kelamin & Tanggal Lahir
  - Usia, Ulang Tahun, Zodiak
  - Pasaran Jawa & Uniqcode
- ℹ️ Sidebar informatif tentang keterbatasan data
- 🎨 Animasi halus & UX intuitif
- 🚀 Tanpa backend — semua diproses via API eksternal

---

## 🛠 Teknologi yang Digunakan

- **HTML5**, **CSS3**, **JavaScript (Vanilla)**
- Font: [Inter](https://fonts.google.com/specimen/Inter) (modern & readable)
- Ikon: [Font Awesome](https://fontawesome.com/)
- Hosting: Bisa dijalankan di **GitHub Pages**, Netlify, Vercel, atau static hosting apa pun

---

## 🌐 Demo Langsung

🔗 [https://abiq.dev/nik-parser](https://abiq.dev/nik-parser)  
*(Ganti dengan URL live-mu setelah deploy)*

---

## 📥 Cara Menjalankan Lokal

1. Clone repositori ini:
```bash
   git clone https://github.com/abiq/nik-parser.git
   cd nik-parser
```

2. Buka file `index.html` di browser:
```bash
   open index.html  # macOS
   start index.html # Windows
   xdg-open index.html # Linux
```

> Tidak perlu server — ini pure static site!

---

## ⚙️ API Backend

Aplikasi ini menggunakan **Google Apps Script** sebagai backend untuk parsing NIK:https://script.google.com/macros/s
/AKfycbwwGKJ6JU7xyfpl
_fwQpjsOjzoHZAUzTyOsnXJnbNuDyTx8aqvx5OX8TXHGKUT-OTh5/exec

> ⚠️ API ini hanya menerima parameter `nik` via **GET request**.

---

## 📝 Catatan Privasi

- **Tidak ada data NIK yang disimpan** di server.
- Semua permintaan dikirim langsung dari browser ke API.
- Aplikasi ini **hanya untuk tujuan edukasi dan eksplorasi teknis**.

---

## 👤 Pembuat

Dibuat dengan ❤️ oleh **[Abiq Nurmagedov](https://instagram.com/ab.iqqq)**  
Instagram: [@ab.iqqq](https://instagram.com/ab.iqqq)  
Email: abiq@rommiui.com

---

## 📄 Lisensi

Proyek ini bersifat **open-source** untuk pembelajaran.  
© 2026 Abiq Nurmagedov. All rights reserved.

---

> 💡 **Ingin kontribusi?** Pull request dan saran selalu diterima!  
> 🐞 Temukan bug? Laporkan di [Issues](https://github.com/abiq/nik-parser/issues).
