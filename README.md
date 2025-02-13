# 🚀 Prediksi Stunting menggunakan Random Forest & Naïve Bayes

## 📌 Ringkasan
Memprediksi **stunting pada balita** menggunakan **Random Forest** & **Naïve Bayes** dengan data dari **Dinas Kesehatan Kabupaten Bekasi**. Pra-pemrosesan data mencakup **ADASYN untuk penyeimbangan** & **K-Fold Cross Validation**.

## 📊 Dataset
- **Sumber:** Dinas Kesehatan Bekasi (April 2024) 🏥
- **Jumlah Data:** 2,255 🧒📊
- **Fitur Utama:** Berat Badan ⚖️, Tinggi Badan 📏, Z-Score 📉

## ⚙️ Metode
✔️ **Pra-pemrosesan:** Pembersihan, Normalisasi, ADASYN 🛠️  
✔️ **Model:** Random Forest 🌲 & Naïve Bayes 🤖 (Gaussian & Bernoulli)  
✔️ **Evaluasi:** Akurasi, Presisi, Recall, F1-Score ✅  

## 🏆 Hasil
| Model                   | Akurasi 🎯 | F1-Score 🏅 |
|-------------------------|------------|------------|
| Random Forest 🌲        | **89.62%**  | **89.09%**  |
| Naïve Bayes (Gaussian) 🤖 | 88.72%     | 88.81%     |
| Naïve Bayes (Bernoulli) ⚡ | 67.83%     | 69.72%     |

## 🚀 Cara Menggunakan
1️⃣ Instal dependensi:  
```sh
pip install -r requirements.txt
```
2️⃣ Jalankan model:  
```sh
python train_model.py
```

## 🔍 Pengembangan Selanjutnya
✨ Coba **XGBoost** atau **Deep Learning** 🧠  
✨ Perluas dataset untuk generalisasi lebih baik 📊  
✨ Tingkatkan rekayasa fitur ⚙️  

## 📜 Lisensi
Dilindungi di bawah lisensi **Creative Commons Attribution 4.0** ✨

## 🙌 Kutipan
📖 **Chintya Annisah Solin, Putu Harry Gunawan**  
"Analisis Prediksi Stunting pada Balita Menggunakan Random Forest & Naïve Bayes," BITS, 2023.
