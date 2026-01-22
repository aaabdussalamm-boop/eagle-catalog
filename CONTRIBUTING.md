# 🤝 Panduan Kontribusi

Terima kasih atas minat Anda untuk berkontribusi ke **Eagle Catalog**! 🎉

Kami menerima kontribusi desain PCB dari siapa saja. Baik Anda seorang hobbyist, mahasiswa, atau profesional - kontribusi Anda sangat dihargai!

## 📋 Apa yang Bisa Dikontribusikan?

- ✅ File schematic Eagle (.sch)
- ✅ File board layout Eagle (.brd)
- ✅ Custom libraries Eagle (.lbr)
- ✅ Screenshot/preview desain (.png, .jpg)
- ✅ Dokumentasi tambahan (.pdf, .txt)
- ✅ File Gerber (untuk produksi)

## 🚀 Cara Berkontribusi (Langkah Mudah)

### **Metode 1: Via GitHub Web (Paling Mudah - Tanpa Install Apa-apa)**

#### 1️⃣ **Fork Repository**
- Klik tombol **"Fork"** di pojok kanan atas halaman repository ini
- Repository akan ter-copy ke akun GitHub Anda

#### 2️⃣ **Upload File Anda**
- Buka repository yang sudah di-fork di akun Anda
- Navigasi ke folder yang sesuai (lihat struktur folder di bawah)
- Klik **"Add file"** → **"Upload files"**
- Drag & drop file .sch dan .brd Anda
- Tambahkan pesan commit, contoh: "Add LM358 audio amplifier"

#### 3️⃣ **Buat Pull Request**
- Klik tombol **"Contribute"** → **"Open pull request"**
- Beri judul yang jelas, contoh: "Add: LM358 Audio Amplifier Circuit"
- Isi deskripsi dengan detail proyek Anda (lihat template di bawah)
- Klik **"Create pull request"**

#### 4️⃣ **Tunggu Review**
- Saya akan review kontribusi Anda dalam 1-3 hari
- Jika ada yang perlu diperbaiki, saya akan beri komentar
- Setelah disetujui, file Anda akan masuk ke repository utama! 🎉

---

### **Metode 2: Via Git Command Line (Untuk yang Familiar dengan Git)**

```bash
# 1. Fork repository via GitHub web interface

# 2. Clone fork Anda
git clone https://github.com/USERNAME-ANDA/eagle-catalog.git
cd eagle-catalog

# 3. Buat branch baru
git checkout -b add-nama-proyek-anda

# 4. Tambahkan file Anda ke folder yang sesuai
# (Copy paste file .sch dan .brd Anda)

# 5. Commit perubahan
git add .
git commit -m "Add: Nama Proyek Anda"

# 6. Push ke GitHub
git push origin add-nama-proyek-anda

# 7. Buat Pull Request via GitHub web interface
```

---

## 📁 Struktur Folder

Tolong upload file Anda ke folder yang sesuai dengan kategori:

```
eagle-catalog/
├── projects/
│   ├── biomedical/          # Proyek biomedical (ECG, EMG, dll)
│   │   └── nama-proyek/
│   │       ├── schematic.sch
│   │       ├── board.brd
│   │       ├── preview.png  (opsional)
│   │       └── README.md    (opsional)
│   │
│   ├── audio/               # Proyek audio (preamp, filter, dll)
│   │   └── nama-proyek/
│   │
│   ├── power-supply/        # Power supply (regulator, inverter, dll)
│   │   └── nama-proyek/
│   │
│   ├── iot-embedded/        # IoT & Embedded systems
│   │   └── nama-proyek/
│   │
│   └── others/              # Kategori lainnya
│       └── nama-proyek/
│
└── libraries/               # Custom Eagle libraries
    └── nama-library.lbr
```

**Tips Penamaan Folder:**
- Gunakan huruf kecil semua
- Gunakan dash (-) untuk spasi
- Contoh: `lm358-audio-amp`, `esp32-sensor-board`

---

## 📝 Template Pull Request

Saat membuat Pull Request, mohon gunakan format ini:

```markdown
## Nama Proyek
[Nama proyek Anda]

## Kategori
- [ ] Biomedical
- [ ] Audio
- [ ] Power Supply
- [ ] IoT & Embedded
- [ ] Lainnya: _________

## Deskripsi
Jelaskan fungsi dan tujuan proyek Anda. Contoh:
- Rangkaian preamp mic menggunakan LM358
- Input: Mic elektret
- Output: Line level
- Supply: 9V DC

## Komponen Utama
- IC1: LM358
- R1, R2: 10K
- C1: 100uF
- dll...

## File yang Diupload
- [ ] Schematic (.sch)
- [ ] Board layout (.brd)
- [ ] Preview/Screenshot (.png)
- [ ] Library (jika ada custom parts)
- [ ] Dokumentasi tambahan

## Testing
- [ ] Schematic sudah di-check DRC (Design Rule Check)
- [ ] Board layout sudah di-check DRC
- [ ] File bisa dibuka di Eagle tanpa error

## Screenshot (Opsional)
[Sisipkan screenshot schematic atau board Anda]

## Catatan Tambahan
[Tambahan informasi jika ada]
```

---

## ✅ Checklist Sebelum Submit

Pastikan sudah:
- [ ] File .sch dan .brd bisa dibuka di Eagle tanpa error
- [ ] Sudah jalankan DRC (Design Rule Check)
- [ ] Nama komponen dan value sudah jelas
- [ ] File diupload ke folder yang benar
- [ ] Commit message jelas dan deskriptif
- [ ] Pull Request menggunakan template di atas

---

## 🎨 Tips untuk Kontribusi Berkualitas

### **1. Beri Nama yang Jelas**
❌ Bad: `untitled.sch`, `pcb1.brd`  
✅ Good: `lm358-preamp.sch`, `esp32-sensor.brd`

### **2. Tambahkan Value pada Komponen**
Pastikan semua resistor, kapasitor, dll sudah diberi nilai yang jelas.

### **3. Upload Preview/Screenshot**
Screenshot membantu orang memahami desain tanpa membuka Eagle.

Cara membuat preview di Eagle:
1. Buka file .sch atau .brd
2. File → Export → Image
3. Pilih PNG, resolusi 300 DPI
4. Save dengan nama `preview.png`

### **4. Tambahkan README (Opsional tapi Sangat Dihargai)**
Buat file `README.md` di folder proyek Anda dengan info:
- Deskripsi detail
- Bill of Materials (BOM)
- Cara assembly
- Testing procedure
- Known issues (jika ada)

### **5. Respect Copyright**
Pastikan desain yang Anda kontribusikan adalah:
- Original karya Anda, ATAU
- Open source / public domain, ATAU
- Anda punya izin untuk share

---

## 🐛 Melaporkan Bug atau Issue

Jika Anda menemukan:
- File yang corrupt
- Link yang rusak
- Kesalahan informasi
- Saran improvement

Silakan buat **Issue** di GitHub dengan detail yang jelas.

---

## 💬 Butuh Bantuan?

Jika ada pertanyaan atau kesulitan:
1. Buka **[Issues](https://github.com/aaabdussalamm-boop/eagle-catalog/issues)** dan cari apakah pertanyaan Anda sudah dijawab
2. Jika belum, buat Issue baru dengan label "question"
3. Atau kontak saya via email (lihat di profile)

---

## 📜 Lisensi

Dengan berkontribusi ke repository ini, Anda setuju bahwa kontribusi Anda akan dilisensikan di bawah lisensi yang sama dengan repository ini (biasanya MIT License atau Creative Commons).

---

## 🌟 Hall of Fame - Contributors

Terima kasih kepada semua yang telah berkontribusi:
- [Nama Anda akan muncul di sini setelah kontribusi pertama! 🎉]

---

**Terima kasih telah berkontribusi ke Eagle Catalog!** ❤️

Setiap kontribusi, sekecil apapun, sangat berarti untuk komunitas elektronika Indonesia.

Happy designing! 🔌⚡
