# Prediksi Kepuasan Pelanggan E-Commerce

Proyek ini bertujuan untuk memprediksi tingkat kepuasan pelanggan (Low, Medium, High) menggunakan teknik Machine Learning berbasis data interaksi dan karakteristik pelanggan.

## 📁 Struktur Proyek

├── data/
│   └── customer_feedback_satisfaction.csv
├── notebooks/
│   └── Uasss_Final_Edited_Final.ipynb
├── README.md

## 📊 Dataset
Sumber: Dataset e-commerce berisi lebih dari 38.000 data pelanggan
Fitur:

  * Demografi: `Gender`, `Country`, `Age`, `Income`
  * Interaksi: `ProductQuality`, `ServiceQuality`, `FeedbackScore`, `LoyaltyLevel`
  * Target asli: `SatisfactionScore` (0–100)
  * Target klasifikasi: `SatisfactionLevel` (Low, Medium, High)

## 🧪 Model yang Digunakan
* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest (dengan GridSearchCV untuk hyperparameter tuning)

## ⚙️ Preprocessing
* Handling missing & duplicate data
* Encoding data kategorikal dengan `LabelEncoder`
* Normalisasi fitur numerik dengan `StandardScaler`
* Menggunakan `SMOTE` untuk mengatasi ketidakseimbangan kelas target


## 📈 Hasil Evaluasi
* Model terbaik: **Random Forest** dengan hasil evaluasi terbaik berdasarkan akurasi dan F1-score
* Visualisasi meliputi:
  * Distribusi `SatisfactionScore`
  * Heatmap korelasi fitur
  * Classification report

## 📌 Tools
* Python 3.10+
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Pandas, Numpy, Matplotlib, Seaborn


## 👤 Anggota Proyek
* Barokah Sa’adah – EDA (Data collection dan exploratory data analysis), Preprocessing, Model Logistic Regression
* Dwika Oca Ramadhanti – EDA (Data collection dan exploratory data analysis), Preprocessing, Model Random Forest
* Tira Julia Indah Sari – EDA (Data collection dan exploratory data analysis), Preprocessing, Model SVM
* Eka Diana Forensia – Evaluasi Model, Visualisasi ROC, Simpan Model Terbaik dan Penulisan Dokumen


## 🚀 Cara Menjalankan
1. Clone repositori ini
bash
git clone https://github.com/NAMA-KAMU/ml-kepuasan-pelanggan.git
cd ml-kepuasan-pelanggan
2. Jalankan notebook:
bash
jupyter notebook notebooks/Uasss_Final_Edited_Final.ipynb

## 📄 Lisensi
Proyek ini disusun untuk memenuhi tugas UAS Machine Learning dan hanya untuk tujuan pembelajaran.
