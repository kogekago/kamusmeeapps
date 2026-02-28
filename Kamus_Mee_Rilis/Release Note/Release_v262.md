# 🚀 Kamus Mee — Changelog Resmi

---

## 🆕 v2.6.2 (Latest)

**Patch Update — Perbaikan Tampilan About**
📅 1 Maret 2026

### ✨ Pembaruan

* Perbaikan tampilan catatan rilis di halaman **“Tentang”**
* Markdown mentah (`##`, `**`, `---`) tidak lagi muncul di UI
* Catatan rilis kini ditampilkan sebagai ringkasan singkat & informatif
* Bullet list dinormalisasi agar lebih rapi
* Layout lebih bersih di layar HP (tanpa overflow)
* UI tetap stabil jika gagal mengambil data rilis

🎯 Meningkatkan kualitas pengalaman pengguna dan tampilan yang lebih profesional.

---

## 🆕 v2.6.1

**Minor Update — Informasi Versi & Transparansi Sistem**
📅 1 Maret 2026

### ✨ Pembaruan

* Menampilkan versi aplikasi yang sedang digunakan
* Menampilkan versi terbaru (jika tersedia)
* Tautan langsung ke halaman rilis GitHub
* Tombol unduh APK terbaru (jika tersedia)
* Sistem pengecekan update otomatis dari GitHub

### 🛠️ Stabilitas

* Penanganan error koneksi lebih aman
* Tidak menampilkan pesan teknis jika gagal cek update
* Tetap stabil tanpa koneksi internet

🎯 Meningkatkan transparansi versi dan memudahkan distribusi pembaruan APK.

---

## 🆕 v2.5.1

**Stabilitas Sistem & Penyempurnaan Pencarian**

### 📊 Perbaikan Statistik

* Statistik diambil langsung dari pagination API (`count`)
* Menghilangkan error “Endpoint count tidak ditemukan”

### 🌍 Penyempurnaan Filter & Wilayah

* Filter bahasa (`language=`) lebih akurat
* Integrasi penuh endpoint `/api/regions/`
* Dukungan filter berdasarkan `region_id`

### 🔎 Peningkatan Pencarian

* Sistem debounce untuk pencarian lebih responsif
* Prioritas hasil yang diawali huruf yang sama
* Tidak lagi kehilangan hasil akibat filter salah

### 🛠️ Perbaikan Stabilitas

* Penanganan error HTTP (502, 503, 504, 530)
* Timeout & gangguan jaringan ditangani lebih baik
* Fallback parsing JSON lebih aman

### 🚀 Optimasi Performa

* Mengurangi request tidak perlu
* Lebih ringan pada koneksi lambat

🎯 Meningkatkan kestabilan sistem pencarian dan statistik agar Kamus Mee semakin andal sebagai dokumentasi bahasa Mee.

