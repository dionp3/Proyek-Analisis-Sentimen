# 📊 Proyek Analisis Sentimen Ulasan Disney+ Hotstar

**📝 Submission pertama** dari course **Belajar Pengembangan Machine Learning** di Dicoding.  
Proyek ini dikembangkan untuk memenuhi *Learning Objective* dari program **Coding Camp 2025**.

---

## 🎯 Deskripsi Proyek

Proyek ini bertujuan untuk melakukan **analisis sentimen** terhadap ribuan ulasan pengguna aplikasi **Disney+ Hotstar** yang diambil langsung dari **Google Play Store**. Proses analisis melibatkan tahapan:

- Web scraping
- Pra-pemrosesan data teks
- Klasifikasi sentimen menggunakan berbagai model machine learning
- Evaluasi performa model

---

## ✨ Fitur Utama

- 🔍 **Web Scraping**: Mengambil ulasan aplikasi secara langsung dari Google Play Store.
- 🧼 **Preprocessing**: Membersihkan dan menyiapkan data teks untuk analisis lanjutan.
- 📊 **Sentiment Classification**: Mengklasifikasikan ulasan ke dalam kategori **positif**, **netral**, atau **negatif**.
- 🧪 **Model Evaluation**: Menilai performa model berdasarkan metrik akurasi dan lainnya.

---

## 🛠️ Teknologi yang Digunakan

- **Python**
- Web Scraping: `google-play-scraper`, `BeautifulSoup`, `Selenium`
- Data Manipulasi: `Pandas`, `NumPy`
- Text Processing: `NLTK`, `TextBlob`
- Machine Learning: `Scikit-learn`, `TensorFlow`

---

## 🚀 Cara Instalasi

1. **Clone Repository**  
   ```bash
   git clone https://github.com/mfatarsyah/Proyek-Analisis-Sentimen.git
   cd Proyek-Analisis-Sentimen
   ```

2. **Install Dependensi**  
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧠 Model yang Digunakan

### 📌 Model 1: SVM + TF-IDF
- Menggunakan **Support Vector Machine** dengan representasi fitur berbasis **TF-IDF**.
- Dilengkapi dengan teknik **SMOTE** untuk menangani *class imbalance*.

### 🌳 Model 2: Random Forest + TF-IDF
- Menggunakan **Random Forest Classifier** dengan pendekatan yang sama seperti model pertama.

### 🔥 Model 3: Deep Learning (LSTM)
- Menggunakan jaringan saraf berbasis **LSTM** (Long Short-Term Memory).
- Data teks diolah dengan **Tokenizer** dan **Padding** untuk menghasilkan input yang siap diproses.

---

## 🏁 Hasil & Evaluasi

Setelah pelatihan ketiga model, evaluasi dilakukan untuk menentukan model dengan akurasi terbaik.  
Perbandingan antara label sebenarnya dan prediksi ditampilkan untuk menunjukkan seberapa baik model dapat memprediksi sentimen dari ulasan pengguna.

---

## 📄 Lisensi

Proyek ini dilisensikan dengan **MIT License**.  
Silakan digunakan dan dikembangkan kembali dengan tetap mencantumkan atribusi.

---
