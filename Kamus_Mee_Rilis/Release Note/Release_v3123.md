# Kamus Mee v3.12.3 — Submenu lebih jelas

**Tanggal:** 21 November 2026  
**Platform:** Android  
**Versi aplikasi:** 3.12.3 (`versionCode 314`)  
**Berkas:** [Kamus Mee v3.12.3.apk](../android/Kamus%20Mee%20v3.12.3.apk)

## Perubahan

- Submenu **Media Mee** — Beranda, Katalog, Album, dan Artis — memakai warna yang jelas di atas header cokelat.
- Tab aktif ditandai bidang terang dengan teks cokelat tegas; tab lain tetap memakai teks terang. Pengguna dapat mengenali pilihan aktif tanpa hanya mengandalkan perubahan warna teks.
- Tampilan submenu yang sama diterapkan pada **Aktivitas Belajar**, yaitu Lanjutkan dan Riwayat.
- Keempat submenu Media Mee terlihat sekaligus pada layar selebar 320 dan 390 piksel logis dengan ukuran teks normal.
- Pada ukuran teks besar, submenu dapat digulir dan dilengkapi tombol **Submenu berikutnya**, tanpa mengecilkan atau memotong nama menu.
- Warna header tetap konsisten ketika konten digulir.
- Nomor versi cadangan pada aplikasi diselaraskan menjadi 3.12.3.

## Validasi

- Seluruh **114 pengujian Flutter lulus**.
- Pengujian submenu mencakup mode terang dan gelap, layar sempit, perpindahan tab, serta skala teks 160%.
- Kontras teks submenu memenuhi rasio minimal **4.5:1**; penanda tab aktif minimal **3:1**.
- Area sentuh tab minimal 48 piksel logis.
- Build APK mode release berhasil. Pemeriksaan statis tidak menemukan error atau warning; masih terdapat informasi deprecation/lint dari SDK dan kode yang ada.

## Catatan distribusi

APK ini dibangun dalam mode release, tetapi masih menggunakan **signing debug** sesuai konfigurasi proyek. Berkas disimpan untuk pengujian lokal; belum dipublikasikan ke toko aplikasi atau GitHub Releases dalam pekerjaan ini.

SHA-256 APK:

```text
145817290F397087618BD275E2C88D20B5B821BB6DDD5686F34758CC9E345CBF
```

Catatan ini menjelaskan perubahan v3.12.3. Catatan versi terdahulu tetap tersedia sebagai arsip di direktori ini.
