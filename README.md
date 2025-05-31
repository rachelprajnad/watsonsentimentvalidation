# Analisis Ulang Data Tweet Kaggle Menggunakan IBM Watson NLU untuk Validasi dan Evaluasi Akurasi Sentimen

## Project Overview
Dataset tweet yang digunakan berasal dari Kaggle, sudah menyertakan label sentimen asli (`positive`, `neutral`, `negative`). Proyek ini bertujuan melakukan analisis ulang sentimen menggunakan IBM Watson Natural Language Understanding (NLU) untuk memvalidasi dan mengevaluasi akurasi hasil analisis Watson terhadap label asli pada dataset.

Dengan membandingkan prediksi Watson dan label asli, proyek ini memberikan gambaran seberapa baik layanan AI Watson dalam menganalisis sentimen tweet berbahasa Inggris.

## Raw Dataset Link
Dataset yang digunakan:  
- [Kaggle Twitter Airline Sentiment Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)  
Dataset ini berisi kolom `text` dan kolom `airline_sentiment` yang merupakan label sentimen asli.

## Insight & Findings
- Dataset sudah memiliki label sentimen asli untuk validasi hasil analisis.  
- Melalui preprocessing, teks tweet dibersihkan dari URL, mention, hashtag, emoji, dan karakter non-ASCII agar input ke Watson lebih optimal.  
- Analisis Watson menghasilkan label dan skor sentimen yang kemudian dibandingkan dengan label asli untuk mengukur akurasi.  
- Ditemukan area dimana Watson kuat dalam prediksi sentimen dan beberapa kasus dimana hasil berbeda, memberikan insight untuk perbaikan analisis sentimen berbasis AI.

## AI Support Explanation
- IBM Watson Natural Language Understanding (NLU) digunakan untuk menganalisis sentimen tweet.  
- NLU memberikan label sentimen prediksi dan skor confidence.  
- Hasil analisis dibandingkan dengan label asli dari dataset untuk evaluasi performa.  
- Proses ini membantu memvalidasi keandalan model Watson dalam konteks tweet nyata.

---

## Cara Menjalankan

1. Download dataset dari link Kaggle dan letakkan file `Tweets.csv` di folder kerja.  
2. Install dependencies dengan:  
