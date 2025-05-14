##🧾 Prediksi Harga Rumah: Model Machine Learning untuk Estimasi Nilai Properti
Tempat pengumpulan capstones 3
Notebook ini menyajikan pipeline prediktif lengkap untuk memperkirakan harga rumah berdasarkan fitur-fitur properti yang tersedia. Proyek ini bertujuan untuk:

Meningkatkan akurasi estimasi harga rumah

Menerapkan teknik Machine Learning yang tepat untuk regresi

Mengoptimalkan preprocessing dan seleksi fitur

🎯 Tujuan Proyek
Membangun model prediktif berbasis data yang mampu memperkirakan harga rumah secara akurat, sebagai solusi dalam pengambilan keputusan jual-beli properti atau sebagai dasar sistem rekomendasi properti online.

🗂️ Isi Notebook
Notebook ini terdiri atas beberapa tahapan utama:

Eksplorasi Data Awal & Pembersihan Data

Menangani missing values

Deteksi dan penanganan outlier

Transformasi variabel kategorikal dan numerik

Feature Engineering

Encoding variabel kategorikal

Transformasi log dan scaling

Seleksi fitur

Modeling & Evaluasi

Linear Regression, Ridge, Lasso, dan XGBoost

Evaluasi model dengan RMSE

Cross-validation dan hyperparameter tuning

Deployment Model

Menyimpan model menggunakan joblib

Prediksi terhadap data baru

📌 Hasil Utama
Model XGBoost Regressor menghasilkan performa terbaik dengan RMSE terendah.

Fitur penting seperti OverallQual, GrLivArea, dan TotalBsmtSF terbukti paling berpengaruh terhadap harga rumah.

Pipeline berhasil dikembangkan untuk prediksi harga terhadap data yang belum diketahui nilai targetnya.

🧰 Teknologi yang Digunakan
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Joblib

📎 Catatan Tambahan
Model ini cocok digunakan untuk membantu agen properti atau sistem online dalam memberikan estimasi harga awal terhadap properti berdasarkan fitur fisik dan lokasi.
