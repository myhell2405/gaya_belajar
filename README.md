# 🎓 Analisis Gaya Belajar Siswa MTsN 1 Kota Padang TP 2024/2025

Proyek ini bertujuan untuk menganalisis hasil asesmen gaya belajar siswa MTsN 1 Kota Padang berdasarkan kuisioner non-kognitif. Setiap jawaban dikategorikan ke dalam tiga tipe gaya belajar: **Visual**, **Auditori**, dan **Kinestetik**.

---

## 📊 Tujuan Analisis

- Mengidentifikasi gaya belajar dominan masing-masing siswa.
- Menyajikan visualisasi statistik distribusi siswa berdasarkan tipe belajar.
- Memberikan rekomendasi pendekatan pembelajaran yang adaptif bagi tenaga pendidik.

---

## ⚙️ Teknologi & Library

- **Python 3.10+**
- **Pandas** (Data manipulation & processing)
- **Matplotlib** (Data visualization)
- **Jupyter Notebook** (Interactive analysis environment)

---

## 📁 Struktur Berkas

`	ext
gaya_belajar/
├── data_belajar.xlsx                # Data mentah kuesioner siswa
├── analisis_gaya_belajar.ipynb      # Notebook langkah pembersihan & analisis data
├── hasil_analisis_gaya_belajar.xlsx # Hasil pengelompokan gaya belajar siswa
├── grafik_bar_gaya_belajar.png      # Visualisasi diagram batang
├── grafik_pie_gaya_belajar.png      # Visualisasi diagram lingkaran
├── .gitignore                       # File pengabaian cache git
└── README.md                        # Dokumentasi proyek
`

---

## 📌 Metodologi Analisis

1. **Import Data**: Membaca data jawaban kuesioner dari berkas Excel.
2. **Data Cleaning**:
   - Ekstraksi opsi pilihan pertama dari setiap respons.
   - Validasi format respons (A, B, atau C).
3. **Kategorisasi**:
   - **Opsi A** → Visual
   - **Opsi B** → Auditori
   - **Opsi C** → Kinestetik
4. **Agregasi**: Menghitung frekuensi preferensi per siswa dan menentukan gaya belajar dominan.
5. **Visualisasi**: Membangun visualisasi perbandingan (Bar Chart & Pie Chart).
6. **Ekspor**: Menyimpan rekapitulasi ke format Excel siap pakai.

---

## 🧠 Interpretasi Karakteristik

- **Visual**: Belajar optimal melalui stimulus gambar, diagram alir, dan representasi visual.
- **Auditori**: Belajar lebih efektif melalui instruksi verbal, mendengarkan, dan diskusi.
- **Kinestetik**: Belajar maksimal dengan keterlibatan fisik, simulasi, dan praktik langsung.

---

## 👤 Pengembang

**Helmy Akrim, S.Kom**  
*Sarjana Sistem Informasi \| Data & Systems Analyst*