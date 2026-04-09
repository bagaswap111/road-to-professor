# 🎓 Road to Professor

**Simulasi Karier Dosen Menuju Guru Besar dengan Gaya Modern & Gamifikasi**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Web App](https://img.shields.io/badge/Platform-Web-blue)](https://github.com/yourusername/road-to-professor)
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://roadtoprofessor.netlify.app)

> Sebuah aplikasi web interaktif yang membantu dosen di Indonesia merencanakan perjalanan akademik dari jabatan awal hingga mencapai **Profesor/Guru Besar**. Dilengkapi dengan target kegiatan terukur, milestone tahunan, quest/syarat wajib, serta fitur ekspor PDF. Tampilan ramah Gen Z dengan desain modern, glassmorphism, dan animasi halus.

**🔗 Live Demo: [https://roadtoprofessor.netlify.app](https://roadtoprofessor.netlify.app)**

---

## ✨ Fitur Unggulan

- 🎮 **Quest System** – Syarat wajib untuk setiap jenjang (Lektor, Lektor Kepala, Profesor) berdasarkan regulasi terbaru.
- 📊 **Target Kegiatan Terukur** – Hitung otomatis kebutuhan publikasi, beban mengajar (SKS), bimbingan mahasiswa, dan pengabdian.
- 📈 **Milestone Tahunan** – Grafik interaktif + rincian per tahun untuk AK kumulatif dan jumlah publikasi.
- 📄 **Ekspor PDF** – Cetak seluruh laporan (quest, target kegiatan, grafik, milestone) dalam satu file.
- 📬 **Request Feature via Email** – Kirim saran langsung ke pengembang melalui modal.
- 🧩 **Variabel Dinamis** – Ubah jenjang, AK, pengalaman, target durasi, intensitas riset, publikasi, dan prestasi.
- 🌈 **UI/UX Modern** – Glassmorphism, warna kalem, kartu interaktif, tipografi nyaman.

---

## 🚀 Cara Menggunakan

### Prasyarat
- Browser modern (Chrome, Firefox, Edge, Safari)
- Koneksi internet (untuk CDN Chart.js & html2canvas)

### Langkah-langkah

1. **Buka file `index.html`** di browser (double click atau buka dengan live server).

2. **Isi variabel** di panel kiri sesuai kondisi Anda saat ini:
   - Jenjang, AK, pengalaman, gelar, sertifikasi
   - Target karier (Profesor / Lektor Kepala / Lektor) dan durasi
   - Intensitas riset (rendah/sedang/tinggi)
   - Jumlah publikasi yang sudah dimiliki (Q1, Q2, Q3, dll)
   - Prestasi tambahan (centang kartu)

3. **Klik tombol "SIMULASI & MILESTONE"** untuk melihat hasil:
   - Quest/syarat wajib (centang hijau/merah)
   - Target kegiatan terukur (berapa publikasi, SKS, bimbingan, pengabdian)
   - Grafik milestone + rincian per tahun

4. **Klik "UNDUH PDF"** untuk menyimpan laporan lengkap.

5. **Klik "REQUEST FEATURE"** untuk mengirim saran melalui email.

---

## ⚙️ Teknologi yang Digunakan

- **HTML5** – Struktur semantik
- **CSS3** – Flexbox, Grid, Glassmorphism, animasi
- **JavaScript (Vanilla)** – Logika simulasi, manipulasi DOM
- **Chart.js** – Grafik milestone interaktif
- **html2canvas + jsPDF** – Ekspor PDF dari elemen DOM
- **Google Fonts (Inter)** – Tipografi modern

---

## 📁 Struktur File
```
road-to-professor/
├── index.html # Aplikasi utama (all-in-one)
├── README.md # Dokumentasi ini
└── assets/ (optional) # Screenshot / demo
```


> Aplikasi ini **self-contained** – hanya satu file HTML yang berisi style, script, dan markup.

---

## 🧮 Logika Perhitungan (Ringkasan)

- **Target AK** : Profesor = 850, Lektor Kepala = 400, Lektor = 200.
- **Sisa AK** = Target AK – (AK awal + AK dari publikasi yang sudah dimiliki + bonus sertifikasi).
- **Proporsi Tri Dharma** : Riset 45%, Pendidikan 35%, Pengabdian 20%.
- **Publikasi wajib** :
  - Lektor: 1 artikel Q3/Sinta2
  - Lektor Kepala: 1 artikel Q2
  - Profesor: 1 Q2 + 1 Q3/Sinta1 (atau 2 Q1 jika fast track)
- **Prestasi tambahan** : minimal 1 untuk profesor (ketua hibah, reviewer, penghargaan, promotor S3, keynote).
- **Milestone** : Distribusi linear sisa AK dan estimasi publikasi berdasarkan intensitas riset.

---

## 🤝 Kontribusi

Kontribusi sangat diterima! Jika Anda menemukan bug atau memiliki ide fitur baru:

1. **Fork** repositori ini
2. Buat branch fitur (`git checkout -b fitur-keren`)
3. Commit perubahan (`git commit -m 'Tambahkan fitur X'`)
4. Push ke branch (`git push origin fitur-keren`)
5. Buat **Pull Request**

Atau langsung gunakan tombol **"REQUEST FEATURE"** di aplikasi untuk mengirim saran via email.

---

## 📬 Kontak & Lisensi

- **Pengembang**: Bagas Saputra
- **Email**: bagassaputra69@gmail.com
- **Lisensi**: MIT – bebas digunakan, dimodifikasi, dan didistribusikan untuk keperluan akademik maupun komersial.

---

## 🙏 Ucapan Terima Kasih

- Regulasi **Kepmendiktisaintek No. 39 Tahun 2026** dan **Permendiktisaintek No. 52 Tahun 2025** sebagai acuan poin & syarat.
- Tim **PAK (Penilaian Angka Kredit)** di berbagai PT yang telah berbagi wawasan.
- Komunitas dosen Indonesia yang selalu semangat menuju Guru Besar!

---

<div align="center">
  <sub>Made with ☕ and 🎓 for Indonesian academics.</sub>
</div>
