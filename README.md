# KTP Checker 17 – Parser NIK KTP Indonesia

![KTP Checker 17 Preview](https://via.placeholder.com/800x450/3a86ff/ffffff?text=KTP+Checker+17+Preview)
*(Screenshot aktual akan ditampilkan setelah deploy)*

Aplikasi web ringan untuk menerjemahkan 16 digit NIK (Nomor Induk Kependudukan) dari KTP Indonesia menjadi informasi terstruktur seperti provinsi, kabupaten/kota, jenis kelamin, tanggal lahir, usia, zodiak, dan lainnya — langsung di browser, tanpa instalasi.

> ⚠️ **Catatan Penting:** Data yang dihasilkan hanya berdasarkan struktur resmi NIK. Informasi lokasi mencerminkan tempat pertama kali NIK dibuat atau tempat lahir, **bukan domisili pemilik saat ini**.

---

## 🔍 Fitur Utama

- ✅ Parsing NIK 16 digit secara real-time
- 🌐 Desain premium minimalist yang responsif (mobile & desktop)
- 📊 Menampilkan informasi lengkap:
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

- **HTML5, CSS3, JavaScript (Vanilla)**
- **Font:** Inter
- **Ikon:** Font Awesome
- **Hosting:** Kompatibel dengan GitHub Pages, Netlify, Vercel, dll.

---

## 🌐 Demo Langsung

🔗 **[https://abiqnurmagedov17.github.io/KTP-Checker17](https://abiqnurmagedov17.github.io/KTP-Checker17)**

*(Aktifkan GitHub Pages di Settings → Pages → Branch: main, Folder: /root)*

---

## 📥 Cara Menjalankan Lokal

1. Clone repositori:
   ```bash
   git clone https://github.com/abiqnurmagedov17/KTP-Checker17.git
   cd KTP-Checker17
```

1. Buka index.html di browser favoritmu:
   ```bash
   open index.html
   # atau langsung buka file di browser
   ```

Tidak perlu server — ini pure static HTML/CSS/JS!

---

⚙️ API Backend

Aplikasi ini menggunakan Google Apps Script sebagai layanan parsing:

```
https://script.google.com/macros/s/AKfycbwwGKJ6JU7xyfpl_fwQpjsOjzoHZAUzTyOsnXJnbNuDyTx8aqvx5OX8TXHGKUT-OTh5/exec?nik=
```

Respons berupa JSON dengan status success jika NIK valid.

---

📝 Privasi & Etika

· ❌ Tidak ada data NIK yang disimpan di server
· 🔒 Semua permintaan dikirim langsung dari browser ke API
· 🎯 Aplikasi ini hanya untuk edukasi dan eksplorasi teknis — jangan gunakan untuk tujuan ilegal atau pelanggaran privasi

---

👤 Pembuat

Dibuat oleh Abiq Nurmagedov

· Instagram: @ab.iqqq
· GitHub: @abiqnurmagedov17

---

📄 Lisensi

© 2026 Abiq Nurmagedov. All rights reserved.
Proyek ini bersifat open untuk pembelajaran pribadi.

---

💡 Ingin kontribusi? Pull request diterima!
🐞 Temukan bug? Laporkan di Issues.

```© 2026 Abiq Nurmagedov. All rights reserved.

---

> 💡 **Ingin kontribusi?** Pull request dan saran selalu diterima!  
> 🐞 Temukan bug? Laporkan di [Issues](https://github.com/abiq/nik-parser/issues).
