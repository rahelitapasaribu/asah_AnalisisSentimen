# Analisis Sentimen Review Gojek

Proyek ini merupakan submission course **Deep Learning** di Dicoding, guna memenuhi **Mandatory Achievement 4: Asah**, yang dipimpin oleh Dicoding Indonesia bekerja sama dengan Accenture. 

Proyek ini bertujuan untuk menganalisis sentimen pengguna terhadap layanan Gojek menggunakan berbagai metode **Machine Learning** dan **Deep Learning**.

---

## Dataset

- Dataset diperoleh dari proses **scraping review Gojek**.
- Total data: sekitar **100.000 review**.
- Setiap review sudah melalui **preprocessing**:
  - Pembersihan teks (menghapus URL, mentions, karakter non-alfanumerik)
  - Stopword removal
  - Stemming (Sastrawi)
- Label sentimen: **negative, neutral, positive**

---

## Fitur dan Metode

1. **Feature Extraction**
   - Bag-of-Words (BoW)
   - TF-IDF
   - Word2Vec embedding
   - Tokenizer + padding sequences untuk input ke LSTM

2. **Machine Learning**
   - **SVM**: klasifikasi sentimen menggunakan fitur TF-IDF / BoW

3. **Deep Learning**
   - **LSTM**: model sequential dengan embedding layer Word2Vec
   - Evaluasi dengan **accuracy, precision, recall, F1-score, confusion matrix**


## Struktur Folder

