# 🔐 Mifare Classic Access Bits Calculator

![GitHub Repo stars](https://img.shields.io/github/stars/username/repo?style=for-the-badge&color=ffd700)
![GitHub license](https://img.shields.io/github/license/username/repo?style=for-the-badge&color=38bdf8)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-10b981?style=for-the-badge)

> **"Stop bricking your RFID cards!"** > Alat web-based paling presisi untuk mendekode dan mengkodekan Access Bits Mifare Classic (Bytes 6, 7, 8) tanpa ribet buka datasheet manual.

---

## 🛠 Mengapa Kamu Membutuhkan Alat Ini?
Menulis *Access Bits* ke kartu Mifare adalah proses yang berisiko tinggi. Salah satu bit saja, kartu/sektor Anda akan **terkunci selamanya (Bricked)**. 

Alat ini hadir untuk:
- ✅ **Menghilangkan Tebakan**: Lihat hasil konfigurasi Anda secara visual sebelum melakukan *write*.
- ✅ **Akurasi 100%**: Menggunakan algoritma inversi bit resmi sesuai datasheet NXP.
- ✅ **Efisiensi Waktu**: Tidak perlu menghitung manual bit-per-bit yang membingungkan.

## ✨ Fitur Utama
- 🎨 **Deep Dark Mode UI**: Tampilan modern, futuristik, dan nyaman di mata.
- 🔍 **Instant Decoder**: Tempelkan 6 karakter Hex, dan lihat semua hak akses Key A, Key B, dan Bits terbuka secara transparan.
- 🏗️ **Visual Encoder**: Klik dan ubah bit langsung di tabel, lalu salin Hex yang dihasilkan.
- 📑 **Integrated Cheat Sheet**: Referensi aturan lengkap untuk Data Blocks & Sector Trailer langsung di layar Anda.
- 🚨 **Safety Highlighting**: Peringatan otomatis jika Anda menyetel konfigurasi yang berisiko tinggi (Akses "Never").

## 📸 Preview Tampilan
!

## 🚀 Cara Mulai Cepat
1. Masukkan nilai **Access Bytes** (Default: `FF0780`).
2. Tekan **Decode Hex**.
3. Sesuaikan bit pada tabel sesuai kebutuhan sistem Anda.
4. Klik **Re-Encode** dan gunakan hasilnya di aplikasi RFID Anda (MFRC522, ACR122U, Libnfc, dll).

## 💡 Beri Bintang Jika Bermanfaat! ⭐
Jika alat ini menyelamatkan kartu Anda dari kerusakan atau mempermudah pekerjaan Anda, **tolong beri repositori ini Star!** Itu adalah bentuk dukungan gratis yang sangat berarti bagi pengembang untuk terus memperbarui alat ini.

---

## 🤝 Kontribusi
Punya saran fitur atau menemukan bug? Jangan ragu untuk membuka [Issue](https://github.com/username/repo/issues) atau melakukan *Pull Request*. Kontribusi Anda sangat dihargai!

## 📜 Lisensi
Dilisensikan di bawah **MIT License**. Gunakan dengan bijak.

---
*Developed with ☕ and passion for the RFID community.*
