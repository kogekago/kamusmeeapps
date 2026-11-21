# Kamus Mee v3.12.4 — Keamanan dan kunci rilis

Tanggal: 21 November 2026
Versi Android: `3.12.4+315`
Status: kandidat lokal, belum dipublikasikan ke GitHub Releases.

[Berkas APK](../android/Kamus%20Mee%20v3.12.4.apk)

- APK ditandatangani kunci RSA 4096 khusus rilis, bukan Android Debug.
- Build menolak kunci debug meskipun nama berkasnya diganti, dan menolak konfigurasi signing yang hilang.
- Koneksi chat menghentikan percobaan sambung ulang ketika server mencabut akses dengan kode 4403.
- 116 tes Flutter lulus; verifikasi apksigner lulus.
- Backend pendamping: pembatasan kepemilikan entri, validasi jalur artikel, penolakan Basic Auth, validasi origin dan pencabutan akses chat, konfigurasi secret wajib, serta pembaruan dependensi. 672 tes backend lulus dan pemindaian requirements tidak menemukan kerentanan yang diketahui.

## Peralihan dari APK debug lama

Tanda tangan berbeda: APK ini tidak dapat langsung menimpa APK debug lama.
Cadangkan data lokal yang diperlukan sebelum instalasi ulang; penghapusan aplikasi
menghapus preferensi dan token lokal. Data akun yang tersimpan di server tetap di server.
Pemasangan pada perangkat fisik dan migrasi langsung belum diuji.

Keystore disimpan di luar repositori dan harus dicadangkan ke media aman di luar
komputer. Jangan memasukkan keystore atau key.properties ke Git.

## Status penerapan

Backend belum di-deploy. Pembersihan riwayat Git hanya disimpan lokal sesuai
keputusan pemilik; riwayat GitHub belum diganti. Tautan publik web tetap menunjuk
v3.12.3 yang sudah tersedia sampai rilis baru dipublikasikan.

## Integritas

SHA-256 APK: `6d6342d4411819a1ec6f60e258f9d590528b33361360e708bf712276e4389030`

SHA-256 sertifikat: `6a3d7484944636308913b4d38a9e9e9619dcbb7a9e6b105cc5305fcf2028428e`
