# 🔌 Eagle Catalog

[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Projects](https://img.shields.io/badge/projects-4-orange.svg)]()

Koleksi desain PCB untuk aplikasi **Biomedical, Audio, dan Power Supply** menggunakan Autodesk Eagle.

🌐 **Website:** https://aaabdussalamm-boop.github.io/eagle-catalog/

---

## 📂 Daftar Proyek

### ⚕️ Biomedical Electronics

#### 1. **Holter AD - 2 Channel ECG Monitor**
Holter monitor untuk monitoring ECG jangka panjang dengan ESP32 DevKit V1.
- **IC Utama:** 2x AD620, TL084
- **MCU:** ESP32 DevKit V1
- **Fitur:** Dual channel, WiFi/Bluetooth
- **Files:** [`HOLTER AD.sch`](HOLTER%20AD.sch) | [`HOLTER AD.brd`](HOLTER%20AD.brd)

#### 2. **ECG Circuit**
Rangkaian elektrokardiogram single channel dengan DRL circuit.
- **IC Utama:** AD620, TL084, OP07
- **Fitur:** DRL (Driven Right Leg) circuit
- **Files:** [`ecg.sch`](ecg.sch) | [`ecg.brd`](ecg.brd)

---

### 🎵 Audio Electronics

#### 3. **PCG Quad - Preamp & Filter**
Preamp dan filter audio 4-channel menggunakan TL084 dengan built-in voltage inverter.
- **IC Utama:** TL084 (Quad Op-Amp)
- **Power:** Built-in IC 7660 inverter
- **Supply:** ±12V atau ±15V
- **Files:** [`pcg_quad.sch`](pcg_quad.sch) | [`pcg_quad.brd`](pcg_quad.brd)

---

### ⚡ Power Supply

#### 4. **IC 7660 - Voltage Inverter**
Rangkaian pembuat tegangan negatif untuk dual supply op-amp.
- **IC Utama:** ICL7660
- **Input:** +5V hingga +12V DC
- **Output:** -5V hingga -12V DC
- **Arus Max:** 100mA
- **Files:** [`7660.sch`](7660.sch) | [`7660.brd`](7660.brd)

---

## 🚀 Cara Menggunakan

### 1. **Clone Repository**
```bash
git clone https://github.com/aaabdussalamm-boop/eagle-catalog.git
cd eagle-catalog
```

### 2. **Buka di Eagle**
- Download Autodesk Eagle (versi gratis tersedia)
- Buka file `.sch` untuk melihat schematic
- Buka file `.brd` untuk melihat board layout

### 3. **Edit & Customize**
- Modifikasi sesuai kebutuhan Anda
- Jalankan DRC (Design Rule Check)
- Export ke Gerber untuk produksi PCB

---

## 🤝 Kontribusi

**Kami menerima kontribusi dari siapa saja!** 🎉

Apakah Anda punya desain PCB yang ingin dibagikan? Ikuti langkah mudah ini:

### Quick Start:
1. **Fork** repository ini
2. **Upload** file .sch dan .brd Anda
3. **Create Pull Request**
4. Tunggu review (1-3 hari)

📖 **Panduan Lengkap:** Baca [CONTRIBUTING.md](CONTRIBUTING.md) untuk tutorial detail dengan screenshot.

### Yang Bisa Dikontribusikan:
- ✅ Schematic Eagle (.sch)
- ✅ Board layout Eagle (.brd)
- ✅ Custom libraries (.lbr)
- ✅ Preview/screenshot (.png, .jpg)
- ✅ Dokumentasi

---

## 📁 Struktur Folder

```
eagle-catalog/
├── projects/
│   ├── biomedical/       # Proyek biomedical
│   ├── audio/            # Proyek audio
│   ├── power-supply/     # Power supply
│   ├── iot-embedded/     # IoT & embedded
│   └── others/           # Kategori lainnya
├── libraries/            # Custom libraries
├── index.html            # Website
└── README.md
```

---

## 🛠️ Software yang Digunakan

- **Autodesk Eagle** - PCB design software
  - Download: https://www.autodesk.com/products/eagle/free-download
  - Versi gratis tersedia untuk hobbyist

---

## 📚 Resources

### Tutorial Eagle:
- [Eagle Tutorial - Sparkfun](https://learn.sparkfun.com/tutorials/using-eagle-schematic)
- [Eagle Documentation - Autodesk](https://www.autodesk.com/products/eagle/learn)

### Untuk Biomedical Projects:
- ⚠️ **PENTING:** Rangkaian biomedical dalam repository ini untuk tujuan pembelajaran dan penelitian saja
- Tidak boleh digunakan untuk diagnosis medis tanpa sertifikasi yang sesuai
- Selalu gunakan isolated power supply untuk keamanan pasien

### PCB Manufacturing:
- [JLCPCB](https://jlcpcb.com/)
- [PCBWay](https://www.pcbway.com/)
- [OSH Park](https://oshpark.com/)

---

## 🐛 Melaporkan Issue

Menemukan bug atau ada saran? Silakan buat [Issue](https://github.com/aaabdussalamm-boop/eagle-catalog/issues) dengan detail yang jelas.

---

## 📜 Lisensi

Repository ini dilisensikan di bawah [MIT License](LICENSE) - silakan gunakan, modifikasi, dan distribusikan dengan bebas.

Dengan berkontribusi ke repository ini, Anda setuju kontribusi Anda juga akan dilisensikan di bawah MIT License.

---

## 🌟 Contributors

Terima kasih kepada semua yang telah berkontribusi! ❤️

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- Kontributor akan ditambahkan di sini -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

---

## 💬 Kontak

- **GitHub:** [@aaabdussalamm-boop](https://github.com/aaabdussalamm-boop)
- **Website:** https://aaabdussalamm-boop.github.io/eagle-catalog/
- **Issues:** [Create New Issue](https://github.com/aaabdussalamm-boop/eagle-catalog/issues/new)

---

## 🙏 Acknowledgments

- Komunitas elektronika Indonesia
- Autodesk Eagle Community
- Semua kontributor open source

---

**⭐ Jangan lupa beri star jika repository ini bermanfaat!**

Made with ❤️ for the electronics community
