Prediksi Tingkat Kepuasan Pelanggan E-Commerce
Proyek ini bertujuan untuk membangun model klasifikasi machine learning yang mampu memprediksi tingkat kepuasan pelanggan (Low, Medium, High) berdasarkan data karakteristik dan interaksi pelanggan.

📁 Struktur Folder
├── data/
│   └── customer\_feedback\_satisfaction.csv        # Dataset utama
├── notebooks/
│   └── Uasss\_Final\_Edited\_Final.ipynb            # Notebook analisis dan pelatihan model
├── models/
│   └── \[Link model disediakan karena file besar] # File model tidak tersedia langsung
├── README.md                                      

🔍 Dataset
Dataset berisi sekitar 38.000 entri pelanggan, dengan fitur seperti:
- Karakteristik: Gender, Country, Age, Income
- Interaksi: ProductQuality, ServiceQuality, LoyaltyLevel, FeedbackScore
- Target: SatisfactionLevel (Low, Medium, High)

🧠 Model Machine Learning
Model yang dibangun dan diuji:
- Logistic Regression
- SVM (Support Vector Machine)
- Random Forest (dengan GridSearchCV)

Penanganan data tidak seimbang dilakukan dengan *SMOTE*.

Model terbaik adalah Random Forest, yang disimpan dalam format `.joblib`.

📦 Download Model Terlatih
Karena ukuran file >100MB, model tidak diunggah langsung ke GitHub.

Silakan unduh melalui Google Drive:

🔗 [Download best_model_rf.joblib via Google Drive](https://drive.google.com/drive/folders/130BKcPl9IyGHe9Pe4-uulyopmfWjjFeR?usp=sharing)

📊 Visualisasi
Visualisasi disertakan dalam notebook, seperti:
- Histogram distribusi skor kepuasan
- Heatmap korelasi antar fitur
- Grafik evaluasi model

 ✅ Hasil Akhir
Model Random Forest memberikan akurasi dan F1-score terbaik setelah tuning parameter dan penanganan ketidakseimbangan data.

