# ai-clipper-releases
Official desktop releases and installers for AI Video Clipper (Windows x64)


# 🎬 AI Video Clipper — Official Desktop Releases

[![Release](https://img.shields.io/badge/Release-v1.0.0-violet?style=for-the-badge&logo=windows)](https://github.com/wisnusadewa/ai-clipper-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-0078D6?style=for-the-badge&logo=windows11)](https://github.com/wisnusadewa/ai-clipper-releases/releases/latest)
[![Processing](https://img.shields.io/badge/Processing-100%25%20Local%20%26%20Private-emerald?style=for-the-badge&logo=shield)](https://github.com/wisnusadewa/ai-clipper-releases/releases/latest)

> **Pemotong Video Otomatis AI Mandiri untuk Windows**  
> Mengubah video landscape berdurasi panjang menjadi klip vertikal pendek (TikTok, Instagram Reels, YouTube Shorts) dengan deteksi wajah otomatis, transkripsi subtitle offline, dan pemrosesan 100% lokal.

---

## 📥 Unduh Versi Terbaru

| File Installer | Sistem Operasi | Ukuran | Checksum SHA-256 |
| :--- | :---: | :---: | :--- |
| **[AI-Video-Clipper-1.0.0-x64-setup.exe](https://github.com/wisnusadewa/ai-clipper-releases/releases/download/v1.0.0/AI-Video-Clipper-1.0.0-x64-setup.exe)** | Windows 10 / 11 (64-bit) | ~202 MB | `b3d380dd63db8e78ab7c488328f1501ccbb31f5bbdccb8a0d581a139576a17b6` |

👉 **[Lihat Catatan Rilis Lengkap (Releases Page)](https://github.com/wisnusadewa/ai-clipper-releases/releases)**

---

## ✨ Fitur Unggulan

* 🤖 **Smart Auto-Reframe (9:16)**: Deteksi wajah dan fokus subjek dinamis menggunakan MediaPipe Face Detection.
* 🎙️ **Transkripsi Subtitle Lokal**: Otomatis menghasilkan teks subtitle karaoke per-kata tanpa kuota API internet (*powered by Faster-Whisper*).
* 🔒 **Privasi 100% Terjamin**: Video Anda tidak pernah diunggah ke server mana pun. Semua pemrosesan video dilakukan langsung di komputer Anda.
* 🚀 **Zero-Setup Standalone**: Tidak memerlukan instalasi Python, PyTorch, CUDA toolkit, atau Docker tambahan.

---

## 💻 Kebutuhan Sistem Minimum

| Komponen | Spesifikasi Minimum | Rekomendasi |
| :--- | :--- | :--- |
| **OS** | Windows 10 (64-bit) | Windows 11 (64-bit) versi 22H2+ |
| **Prosesor** | Intel Core i5 / AMD Ryzen 5 (4 Cores) | Intel Core i7 / AMD Ryzen 7 (8 Cores) |
| **RAM** | 8 GB | 16 GB atau lebih |
| **Storage** | 2 GB ruang kosong | SSD (NVMe direkomendasikan) |
| **Dependency** | [FFmpeg](https://ffmpeg.org/) terpasang di PATH Windows | `winget install Gyan.FFmpeg` |

---

## 🛠️ Panduan Instalasi Cepat

1. **Unduh Installer**: Klik tautan download di atas atau buka halaman **Releases**.
2. **Jalankan Setup**: Klik dua kali file `AI-Video-Clipper-1.0.0-x64-setup.exe` dan ikuti petunjuk wizard instalasi.
   > *Catatan: Jika muncul peringatan Windows SmartScreen ("Windows protected your PC"), klik **More info** lalu pilih **Run anyway**.*
3. **Pastikan FFmpeg Terpasang**: Buka PowerShell lalu ketik `ffmpeg -version`. Jika belum terpasang, cukup jalankan:
   ```powershell
   winget install Gyan.FFmpeg
   ```
4. Buka aplikasi **AI Video Clipper** dari Desktop atau Start Menu!

---

## 🛡️ Verifikasi Integritas File (SHA-256)

Untuk memverifikasi keaslian file installer yang telah Anda download, jalankan perintah ini di PowerShell:

```powershell
Get-FileHash .\AI-Video-Clipper-1.0.0-x64-setup.exe -Algorithm SHA256
```

Pastikan hash yang dihasilkan cocok dengan:
```text
B3D380DD63DB8E78AB7C488328F1501CCBB31F5BBDCCB8A0D581A139576A17B6
```

---

<p align="center">
  <sub>Web Workspace: <a href="https://ai-clipper-tau.vercel.app">AI Video Clipper Cloud</a> • Dibuat oleh <a href="https://github.com/wisnusadewa">wisnusadewa</a></sub>
</p>
