# 🏡 Prediksi Harga Properti dengan Polynomial Regression

Proyek ini bertujuan untuk memprediksi harga properti berdasarkan luas tanah menggunakan **Polynomial Regression**.  
Eksperimen dilakukan dengan degree 1–5 untuk menemukan model terbaik.

---

## 📁 Dataset
Dataset sederhana berisi kolom:
- `luas_tanah` — ukuran tanah (m²)
- `harga_properti` — harga properti (juta rupiah)

---

## ⚙️ Metode
- **Algoritma**: Polynomial Regression  
- **Tools**: Python, Scikit-learn, Matplotlib, Pandas, NumPy  
- **Evaluasi**: Mean Squared Error (MSE) dan R² Score

---

## 📊 Hasil
| Degree | MSE | R² Score |
|:-------:|:------:|:------:|
| 1 | 12800.32 | 0.893 |
| 2 | 4400.14 | 0.962 |
| 3 | 1580.25 | 0.985 |
| 4 | 1570.80 | 0.986 |
| 5 | 1568.11 | 0.986 |

Model terbaik adalah **degree 3**, dengan R² sebesar **0.985**.

---

## 🖼️ Visualisasi
- `grafik_data_awal.png` → Data Asli  
- `grafik_prediksi_degree3.png` → Prediksi vs Aktual  
- `grafik_error_per_degree.png` → MSE per Degree  

---

## 📘 Kesimpulan
Model polynomial degree 3 menghasilkan performa terbaik tanpa overfitting.  
Cocok digunakan untuk prediksi harga properti dengan pola non-linear.

---

## 🪪 Lisensi
Proyek ini menggunakan lisensi **MIT**.
# UTS-ML
