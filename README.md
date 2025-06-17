# 🎓 Analisis Gaya Belajar Siswa MTsN 1 Kota Padang Tahun Pelajaran 2024/2025

Proyek ini bertujuan untuk menganalisis hasil asesmen gaya belajar siswa MTsN 1 Kota Padang berdasarkan kuisioner non-kognitif. Setiap jawaban dikategorikan ke dalam tiga gaya belajar: Visual, Auditori, dan Kinestetik.

---

## 📊 Tujuan Analisis

- Mengidentifikasi gaya belajar dominan masing-masing siswa
- Menyajikan statistik jumlah siswa berdasarkan gaya belajar
- Memberikan rekomendasi pendekatan pembelajaran yang sesuai

---

## 📁 Struktur Folder

gaya_belajar/
├── data/
│ ├── data_mentah.xlsx # File kuisioner awal dari Google Form
│ └── hasil_analisis_gaya_belajar.xlsx # Hasil analisis akhir
├── grafik/
│ ├── pie_gaya_belajar.png # Pie chart gaya belajar
│ └── bar_gaya_belajar.png # Bar chart gaya belajar
├── notebook/
│ └── analisis_gaya_belajar.ipynb # Notebook Jupyter utama
├── README.md # Dokumentasi proyek ini


---

## ⚙️ Teknologi yang Digunakan

- Python 3.10.12
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📌 Langkah Analisis

1. **Import Data Excel**
2. **Bersihkan data**:
   - Ambil hanya huruf pertama dari setiap jawaban
   - Pastikan jawaban adalah A, B, atau C
3. **Konversi Nilai:**
   - A → Visual
   - B → Auditori
   - C → Kinestetik
4. **Hitung jumlah tiap kategori per siswa**
5. **Tentukan gaya belajar dominan**
6. **Visualisasikan hasil**
7. **Ekspor hasil ke Excel dan gambar grafik**

---

## 🧠 Interpretasi

- **Visual** → Belajar lebih baik dengan gambar, warna, diagram
- **Auditori** → Belajar lebih efektif dengan mendengar dan berdiskusi
- **Kinestetik** → Belajar optimal melalui praktik, gerak, simulasi

---

## 📝 Catatan

- Data bersumber dari kuisioner Google Form.
- Proyek ini dapat dikembangkan lebih lanjut untuk:
  - Analisis per kelas
  - Rekomendasi pembelajaran adaptif
  - Dashboard interaktif

---

## 👤 Penulis

myel  
Mahasiswa Sistem Informasi  
  
