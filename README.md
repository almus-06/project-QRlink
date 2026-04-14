# QRlink — Nexus Premium QR Generator

![QRlink Banner](https://img.shields.io/badge/QRlink-NEXUS_Premium-8ff5ff?style=for-the-badge&logo=qr-code&logoColor=003f43)
![License](https://img.shields.io/badge/Status-Stable-4ade80?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-Vanilla_JS-f1f5f9?style=for-the-badge)

**QRlink** adalah generator QR code berbasis web dengan desain **NEXUS Premium** yang minimalis, futuristik, dan sangat cepat. Dikembangkan khusus untuk kebutuhan personal maupun profesional dengan dukungan fitur pembuatan massal (Batch).

---

## ✨ Features (NEXUS Update)

### 🔵 Single Mode (Real-Time Generation)
- **Instant Preview**: Lihat perubahan gaya secara langsung.
- **Visual DNA**: Kustomisasi warna titik (dots), warna latar belakang, dan bentuk sudut (*Square*, *Rounded*, *Dots*, dll).
- **Precision Export**: Unduh dalam format **PNG (2000x2000px)** untuk kualitas cetak atau **SVG** untuk kebutuhan desain vektor.

### 🟣 Batch Processor (Bento Grid)
- **High Capacity**: Masukkan hingga **50 URL** sekaligus.
- **Bento Preview**: Lihat galeri QR code dalam tata letak kisi (*grid*) yang modern.
- **ZIP Archive**: Unduh seluruh hasil pembuatan QR code dalam satu file kompresi `.zip` dengan sekali klik.

### 🎨 Aesthetics & UX
- **Cyber-Premium Design**: Dilengkapi efek *Animated Orbs*, *Noise Overlay*, dan *Glassmorphism*.
- **Mobile Optimized**: Responsif penuh untuk perangkat mobile dengan *Bottom Navigation Bar*.
- **Reliable Engine**: Menggunakan perbaikan logika ekspor untuk memastikan hasil download selalu siap tanpa error render.

---

## 🛠️ Technical Stack

- **Core**: Vanilla JavaScript (ES6+), HTML5, CSS3.
- **QR Engine**: [qr-code-styling](https://github.com/kozakdenyz/qr-code-styling).
- **ZIP Logic**: [JSZip](https://stuk.github.io/jszip/).
- **File Handling**: [FileSaver.js](https://github.com/eligrey/FileSaver.js/).
- **Icons & Fonts**: Google Material Symbols & Google Fonts (Outfit, Inter).

---

## 🚀 Getting Started

1. **Clone & Open**:
   ```bash
   git clone https://github.com/almus-06/project-QRlink.git
   cd project-QRlink
   ```
2. **Run Locally**:
   Buka file `index.html` langsung di browser atau gunakan server lokal:
   ```bash
   # Contoh jika menggunakan npx
   npx serve .
   ```

---

## 📜 Roadmap & Status
- [x] Dual-Mode Interface (Single & Batch)
- [x] NEXUS Premium UI Overhaul
- [x] ZIP Batch Export (Up to 50 URLs)
- [x] SVG/PNG High-Res Support
- [ ] PWA (Offline Support)
- [ ] Custom Logo Overlay inside QR

---

*Developed with ❤️ by **QRlink Team***
