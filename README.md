# 🚀 Analisis Sentimen Review Aplikasi MyPertamina

Analisis sentimen adalah proses untuk mengidentifikasi dan mengklasifikasikan opini pengguna terhadap suatu produk atau layanan.  
Proyek ini bertujuan untuk menganalisis sentimen dari ulasan pengguna aplikasi **MyPertamina** yang diambil dari Google Play Store.  
Sentimen akan diklasifikasikan ke dalam tiga label: **positif**, **negatif**, atau **netral**.


## **Teknologi yang Digunakan**  
- **Python** (pandas, numpy, scikit-learn, TensorFlow, Google Play Scrapper)  
- **Machine Learning & Deep Learning**  
  - Model **Bi-LSTM**  
  - Model **Bi-GRU**  
  - Model **SVM**  
- **Web Scraping** untuk mengumpulkan dataset  
- **Preprocessing NLP** (stopwords removal, stemming, tokenization)  
- **Git & GitHub** untuk kolaborasi  

## **Prediksi Model**  
Model terbaik mampu mengklasifikasikan sentimen dengan cukup baik. 
Contoh inferensi:  
###**Input:**  
    - "fitur banyak errornya, kamera jelek buram"   
    - "Senang sekali pembayaran lebih mudah"  
    - "Biasa saja"  

###**Prediksi**  
    - "Negative"  
    - "Positive"  
    - "Neutral"  

## **Struktur Proyek**  
📁 Projek analisis sentimen - MyPertamina  
│── 📂 data  
│   ├── ulasan_aplikasi_clean.csv  
│   ├── Label_sentiment.csv   
│── 📂 models   
│   ├── label_mapping.pkl  
│   ├── model_biGRU.h5   
│   ├── model_biLSTM.h5   
│   ├── svm_model.pkl   
│   ├── tdfidf_vectorizer.pkl   
│   ├── tokenizer.pkl   
│── 📂 notebooks     
│   ├── Inference.ipynb   
│   ├── Scraping.ipynb   
│   ├── Sentiment_Analysis_Apk_MyPertamina.ipynb   
│── requirements.txt    
│── README.md    

## **Cara Menjalankan**  
### 1️⃣ Clone repo ini: 
```sh
git clone https://github.com/DumaSitorus/Analisis-Sentiment-ReviewApk-MyPertamina.git
cd Analisis-Sentiment-ReviewApk-MyPertamina 
2️⃣ Install dependensi:
pip install -r requirements.txt
3️⃣ Jalankan model inference:
Buka Inference.ipynb dan jalankan untuk menguji model pada teks baru.


---
📢 Proyek ini bersifat open-source.  
Silakan gunakan, modifikasi, dan kembangkan sesuai kebutuhan kamu.😊
