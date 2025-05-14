# 🏡 JCDS2804 - Capstone Project 3

## 📌 Project Title
**Predictive Modeling of Apartment Sale Prices in Daegu: A Data Science Approach**

---

## 📖 Deskripsi Proyek

Proyek ini bertujuan untuk membangun sistem prediksi harga rumah berdasarkan berbagai fitur properti seperti ukuran, kualitas bangunan, dan lokasi. Dengan pendekatan machine learning, model ini membantu pemangku kepentingan seperti agen properti, pembeli, maupun platform properti digital dalam memperkirakan harga rumah secara lebih objektif dan akurat.

---

## 🎯 Tujuan Proyek

- Memprediksi harga rumah secara akurat menggunakan data historis
- Mengaplikasikan metode regresi dan teknik preprocessing modern
- Mengidentifikasi fitur-fitur properti paling berpengaruh terhadap harga
- Mengembangkan pipeline model yang siap untuk deployment

---

## 🗂️ Struktur Notebook

1. **Eksplorasi & Pembersihan Data**
   - Penanganan nilai kosong (missing values)
   - Deteksi dan penanganan outlier
   - Transformasi fitur kategorikal dan numerik

2. **Feature Engineering**
   - Encoding: One-Hot & Label Encoding
   - Transformasi logaritmik untuk distribusi skewed
   - Standardisasi/normalisasi

3. **Pemodelan**
   - Algoritma: Linear Regression, Ridge, Lasso, XGBoost
   - Evaluasi performa: RMSE, Cross-validation
   - Hyperparameter tuning

4. **Deployment**
   - Simpan model dengan `joblib`
   - Prediksi terhadap data baru tanpa target

---

## 🧪 Teknologi & Tools

- Python 3
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## 📊 Hasil & Insight

- **XGBoost** memberikan hasil terbaik dengan error terendah (RMSE).
- Fitur paling penting:
  - `OverallQual` (Kualitas keseluruhan bangunan)
  - `GrLivArea` (Luas ruang tinggal di atas tanah)
  - `TotalBsmtSF` (Luas basement total)
- Model mampu memberikan prediksi harga rumah yang masuk akal dan stabil.

---

## 🚀 Deployment & Penggunaan

Model telah disimpan dalam bentuk `.pkl` atau `.joblib` dan bisa digunakan untuk prediksi harga pada data baru yang memiliki format serupa, namun belum memiliki nilai target (`SalePrice`).

---

## 📎 Catatan Tambahan

Proyek ini dibuat sebagai bagian dari program capstone bootcamp **Purwadhika Data Science - Batch JCDS2804**.  

---

## 👨‍💻 Author

**Gerald Pascal Ginting**  
📧 Email: [geral.ginting@email.com](mailto:geral.ginting@email.com)  
📍 Purwadhika Data Science Bootcamp  
