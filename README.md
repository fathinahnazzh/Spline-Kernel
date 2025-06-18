# RegresiPolinomial-ForestFires
Proyek ini bertujuan untuk menganalisis dan memprediksi area terbakar di wilayah bagian Utara Portugal menggunakan teknik analisis regresi polinomial.

---

## 📦 Dataset

- Dataset: Forest Fires
- Sumber: http://www.dsi.uminho.pt/~pcortez/forestfires
- Jumlah observasi: 517
- Jumlah variabel: 12
- Variabel target: `Y` (spatial coordinate within the Montesinho park map: 2 to 9)

---

## 🔧 Tools dan Teknologi

- Bahasa Pemrograman: **R**
- IDE: RStudio
- Library yang digunakan:
  - `ggplot2` (visualisasi)
  - `splines` (model spline)
  -  `np` (model kernel)
  - `caret` (machine learning)

---

## 📊 Langkah Analisis

1. Load dan eksplorasi data
2. Pembersihan dan praproses data
3. Seleksi variabel
4. Pembuatan model regresi spline dan kernel
5. Evaluasi model 

---

## 🔍 Hasil Singkat

- Seleksi model menunjukkan bahwa variabel Y (koprdinat spasial) secara signifkan dipengaruhi oleh variabel X (koordinat spasial), DC (kelembapan bahan bakar yang sangat dalam), dan DMC (kelembapan lapisan menengah bahan bakar di hutan)
- Model regresi kernel mampu memberikan nilai R-square lebih tinggi daripada regresi spline.
