# 🇮🇩 KTP Checker 17 – Parser NIK KTP Indonesia

![KTP Checker Preview](https://via.placeholder.com/800x400/fcfcfd/111111?text=KTP+Checker+Preview)  
*(Screenshot aktual akan ditampilkan setelah deploy)*

Aplikasi web ringan untuk **menerjemahkan 16 digit NIK (Nomor Induk Kependudukan)** dari KTP Indonesia menjadi informasi terstruktur seperti provinsi, kabupaten/kota, jenis kelamin, tanggal lahir, usia, zodiak, dan lainnya — **langsung di browser, tanpa instalasi**.

> ⚠️ **Catatan Penting**: Data yang dihasilkan hanya berdasarkan struktur resmi NIK. Informasi lokasi mencerminkan **tempat pertama kali NIK dibuat** atau **tempat lahir**, **bukan domisili pemilik saat ini**.

---

## 🔍 Fitur Utama

- ✅ Parsing NIK 16 digit secara real-time
- 🌐 Desain **premium minimalist** yang responsif (mobile & desktop)
- 📊 Menampilkan:
  - Provinsi & Kabupaten/Kota
  - Kecamatan & Kode Pos
  - Jenis Kelamin & Tanggal Lahir
  - Usia, Ulang Tahun, Zodiak
  - Pasaran Jawa & Uniqcode
- ℹ️ Sidebar informatif (toggleable) tentang keterbatasan data
- 🎨 Animasi halus, loading spinner modern, dan UX intuitif
- 🚀 Pure static site — tidak perlu backend

---

## 🛠 Teknologi

- **HTML5**, **CSS3**, **JavaScript (Vanilla)**
- Font: [Inter](https://fonts.google.com/specimen/Inter)
- Ikon: [Font Awesome](https://fontawesome.com/)
- Hosting: Kompatibel dengan **GitHub Pages**, Netlify, Vercel, dll.

---

## 🌐 Demo Langsung

🔗 [https://abiqnurmagedov17.github.io/KTP-Checker17](https://abiqnurmagedov17.github.io/KTP-Checker17)

*(Aktifkan GitHub Pages di Settings → Pages → Branch: `main`, Folder: `/root`)*

---

## 📥 Cara Menjalankan Lokal

1. Clone repositori:
```bash
   git clone https://github.com/abiqnurmagedov17/KTP-Checker17.git
   cd KTP-Checker17
```

2. Buka `index.html` di browser favoritmu:
```bash
   open index.html
```

> Tidak perlu server — ini pure static HTML/CSS/JS!

---

## ⚙️ API Backend & Sumber Data

Aplikasi ini menggunakan **Google Apps Script** sebagai backend yang mengimplementasikan logika dari library open-source:

> ### 📚 [**nik_parse.js**](https://github.com/bachors/nik_parse.js/)  
> oleh **[Ibnu Bachors](https://github.com/bachors)**

Library ini mampu mendekode struktur NIK sesuai standar administrasi kependudukan Indonesia, termasuk:
- Kode wilayah (provinsi, kabupaten, kecamatan)
- Informasi kelamin & tanggal lahir
- Perhitungan usia, zodiak, pasaran Jawa, dan uniqcode

API:
```bash
   GET https://script.google.com/macros/s/AKfycbwwGKJ
6JU7xyfpl
_fwQpjsOjzoHZAUzTyOsnXJnbNuDyTx8aqvx5OX8T XHGKUT-OTh5/exec?nik=
```

✅ **Kami tidak mengklaim kepemilikan atas logika parsing NIK** — semua kredit teknis untuk decoding NIK diberikan kepada pembuat asli: **Ibnu Bachors**.

---

## 📝 Privasi & Etika

- ❌ **Tidak ada data NIK yang disimpan** di server.
- 🔒 Semua permintaan dikirim langsung dari browser ke API.
- 🎯 Aplikasi ini **hanya untuk edukasi dan eksplorasi teknis** — jangan gunakan untuk tujuan ilegal atau pelanggaran privasi.

---

## 👤 Pembuat

Dibuat oleh **[Abiq Nurmagedov](https://instagram.com/ab.iqqq)**  
- Instagram: [@ab.iqqq](https://instagram.com/ab.iqqq)  
- GitHub: [@abiqnurmagedov17](https://github.com/abiqnurmagedov17)

---

## 🙏 Ucapan Terima Kasih

Terima kasih kepada **[Ibnu Bachors](https://github.com/bachors)** atas kontribusinya dalam membuat [`nik_parse.js`](https://github.com/bachors/nik_parse.js/) — library open-source yang memungkinkan aplikasi seperti ini ada.

---

## 📄 Lisensi

© 2026 Abiq Nurmagedov. All rights reserved.  
Proyek ini bersifat open untuk pembelajaran pribadi.  
Logika parsing NIK mengacu pada library [`nik_parse.js`](https://github.com/bachors/nik_parse.js/) oleh Ibnu Bachors.

---

> 💡 **Ingin kontribusi?** Pull request diterima!  
> 🐞 Temukan bug? Laporkan di [Issues](https://github.com/abiqnurmagedov17/KTP-Checker17/issues).
