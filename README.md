# Clustering Data Menggunakan K-Means dan Silhouette Score

## 📌 Pendahuluan

Proyek ini bertujuan untuk melakukan clustering pada dataset fundamental menggunakan algoritma K-Means dan mengevaluasi hasil clustering dengan Silhouette Score. Selain itu, dilakukan juga Principal Component Analysis (PCA) untuk reduksi dimensi guna meningkatkan kualitas clustering.

## 📂 Dataset

Dataset yang digunakan dalam proyek ini adalah fundamentals.csv yang berisi berbagai fitur numerik dan kategorikal. Dataset ini dianalisis untuk menemukan pola yang tersembunyi di dalamnya melalui teknik clustering.

## 🛠 Teknologi & Library

Proyek ini dibangun menggunakan bahasa Python dengan bantuan beberapa pustaka berikut:

pandas – Untuk manipulasi data

numpy – Untuk komputasi numerik

matplotlib & seaborn – Untuk visualisasi data

sklearn – Untuk preprocessing, clustering, PCA, dan evaluasi

scipy – Untuk deteksi outlier

## 🔍 Metodologi

Eksplorasi Data

Menampilkan informasi dataset

Menangani missing values & data duplikat

Identifikasi kolom numerik dan kategorikal

Preprocessing Data

Encoding data kategorikal dengan LabelEncoder

Normalisasi data numerik menggunakan StandardScaler

Deteksi dan penanganan outlier dengan Z-score

Clustering Data

Menggunakan K-Means Clustering

Menentukan jumlah cluster optimal dengan Elbow Method dan Silhouette Score

Menggunakan PCA untuk reduksi dimensi dan analisis visual

Evaluasi dan Visualisasi

Visualisasi hasil clustering dalam 2D menggunakan PCA

Analisis karakteristik masing-masing cluster

Penyimpanan Hasil

Dataset dengan label cluster disimpan ke file fundamentals_clusters.csv

## 📊 Hasil & Visualisasi

Beberapa hasil utama dari clustering ini meliputi:

Jumlah cluster optimal ditentukan berdasarkan Elbow Method dan Silhouette Score.

Distribusi data dalam cluster divisualisasikan menggunakan PCA 2D scatter plot.

Heatmap korelasi antar fitur untuk memahami hubungan antar variabel.

## 🚀 Cara Menjalankan

Pastikan Anda memiliki Python 3.x dan pustaka yang diperlukan telah diinstal.

Clone repository ini:

git clone https://github.com/username/repository-name.git
cd repository-name

Install dependensi:

pip install -r requirements.txt

Jalankan script utama:

python clustering_script.py

## 📌 Kesimpulan

Dengan menggunakan K-Means dan evaluasi melalui Silhouette Score, dataset berhasil dikelompokkan ke dalam beberapa cluster yang memiliki karakteristik unik. PCA membantu dalam reduksi dimensi untuk meningkatkan pemahaman visual terhadap hasil clustering.
