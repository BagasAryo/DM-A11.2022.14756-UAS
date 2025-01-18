# Poin - poin Dokumentasi Data Mining
[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

1. Klasifikasi Status Gizi Bayi berdasarkan Tinggi Badan, Jenis Kelamin, dan Umur  

2. Permasalahan dari project ini adalah memahami faktor-faktor yang memengaruhi status gizi bayi dengan tujuannya untuk meningkatkan akurasi model decision tree pada dataset ini. Kemudian berikut bagan dari proyek ini
![image](https://github.com/user-attachments/assets/8557450b-d1df-48c5-9313-6a26598f28da)

3. Dataset yang memiliki atribut umur dalam satuan bulan, jenis kelamin, tinggi dalam satuan cm. Setelah dilakukan Exploratory Data Analysis, dataset menunjukkan bahwa perempuan lebih rentan terhadap stunting. 

4. - Persiapan data, menghapus data duplikat dan field yang kosong, encoding feature kategorikal menjadi numerik, membagi dataset menjadi 80% data training dan 20% data testing
   - Pembuatan model Decision Tree, import library DecisionTreeClassifier dari sklearn.tree dan melatih model dengan dataset yang sudah dibagi
   - Evaluasi model, menggunakan model untuk memprediksi status gizi pada data uji (new_data) dan menggunakan accuracy_score, classification_report, dan confusion_matrix untuk mengukur performa

5. ![image](https://github.com/user-attachments/assets/85b5140a-ba6b-48e8-bc8b-448ab0ac2cf3)

6. Hasil dan kesimpulannya adalah akurasi model yang mencapai 98%, yang berarti model decision tree memiliki kemampuan untuk melakukan prediksi sangat baik

## Berikut link experiment selama 1 semester Data Mining
- https://github.com/BagasAryo/DataMining.git
- https://github.com/BagasAryo/Project-based-DM.git

## Persyaratan

- Akun Google Colab
- GDrive
- Dataset Status Gizi Bayi

### Persiapan Dataset

- Download dataset yang ada pada kaggle - https://www.kaggle.com/datasets/rendiputra/stunting-balita-detection-121k-rows/data
- Extract zip file yang sudah didownload, hasil ekstraknya bernama "data_balita.csv".

### Persiapan Google Drive
- Klik tombol Baru di sebelah kiri atas
- Klik tombol Folder Baru, buat folder contohnya bernama Projek status gizi balita
- Upload file data_balita.csv dan buat jalankan file ini pada folder yang sama
- Salin jalur data_balita.csv dan tempel pada pd.read_csv('') untuk impor data

### Mengaktifkan Google Colaboratory (kalau sudah aktif, bisa di skip langkah ini)
- Klik tombol Baru di sebelah kiri atas
- Klik Lainnya
- Klik Hubungkan aplikasi lainnya
- Ketik Colaboratory pada pencarian
- Klik Colaboratory
- Klik Install

Buka google collab
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

