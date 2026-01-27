# 📊 Prediksi Produksi Padi di Pulau Sumatra Tahun 2025

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi produksi padi di Pulau Sumatra pada tahun 2025 menggunakan pendekatan machine learning. Prediksi dilakukan berdasarkan data historis produksi padi, luas panen, dan faktor iklim seperti curah hujan, suhu rata-rata, dan kelembapan.

Pendekatan ini diharapkan dapat memberikan gambaran awal bagi perencanaan ketahanan pangan dan pengambilan keputusan di sektor pertanian.

---

## 🎯 Tujuan
- Menganalisis tren produksi padi di Pulau Sumatra
- Membangun model prediksi produksi padi berbasis data historis
- Membandingkan performa Linear Regression dan Random Forest Regression
- Memprediksi produksi padi di Pulau Sumatra pada tahun 2025

---

## 📂 Dataset
Dataset yang digunakan berasal dari Kaggle dan berisi data tahunan produksi padi di Pulau Sumatra.

**Fitur utama dalam dataset:**
- Tahun
- Provinsi
- Luas Panen (Ha)
- Curah Hujan (mm)
- Suhu Rata-rata (°C)
- Kelembapan (%)
- Produksi Padi (Ton) *(target)*

---

## 🔍 Metodologi
Tahapan pengerjaan proyek ini meliputi:
1. **Data Collection**
2. **Data Understanding**
3. **Data Cleaning**
4. **Exploratory Data Analysis (EDA)**
5. **Feature Engineering**
6. **Data Splitting (Time-Based Split)**
7. **Modeling**
   - Linear Regression (baseline)
   - Random Forest Regression
8. **Hyperparameter Tuning**
9. **Evaluasi Model**
10. **Prediksi Produksi Tahun 2025**

Pembagian data dilakukan berdasarkan urutan waktu untuk menghindari data leakage.

---

## 🤖 Model yang Digunakan
- **Linear Regression**  
  Digunakan sebagai model baseline untuk membandingkan performa.
  
- **Random Forest Regression**  
  Digunakan untuk menangkap hubungan non-linear antar variabel dan memberikan hasil prediksi yang lebih akurat.

---

## 📈 Evaluasi Model
Model dievaluasi menggunakan metrik:
- Mean Absolute Error (MAE)
- R-squared (R²)

Hasil evaluasi menunjukkan bahwa **Random Forest Regression dengan hyperparameter tuning memberikan performa terbaik**.

---

## 🔮 Hasil Prediksi
Berdasarkan model terbaik, produksi padi di Pulau Sumatra pada tahun 2025 diprediksi sebesar:

**≈ 2,42 juta ton**

Prediksi ini menunjukkan adanya **kenaikan moderat** dibandingkan tahun terakhir data historis, dengan asumsi kondisi iklim dan luas panen relatif stabil.

---

## ⚠️ Keterbatasan
- Prediksi dilakukan berdasarkan data historis dan asumsi rata-rata kondisi iklim
- Model belum mempertimbangkan kejadian ekstrem seperti El Niño, bencana alam, atau perubahan kebijakan pertanian
- Prediksi tahun 2025 bersifat estimasi, bukan nilai absolut

---

## 🛠️ Tools & Library
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
