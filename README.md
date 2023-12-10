# Golebooks: Chatbot Book E-Commerce Menggunakan Algoritma Decision Tree


[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1aLGdxKqXZTUqX7vOt9jfF0qmv3KHKRQv?usp=sharing)


Golebooks merupakan chatbot book e-commerce yang dibangun menggunakan model decision tree dan mampu membantu pelanggan untuk mengetahui barnag apa saja yang tersedia, harga barang, dan promo yang sedang berlangsung.

##Metodologi


## Kategori Response Golebooks

- Greeting
- Morning Greeting
- Afternoon Greeting 
- Night Greeting 
- GoodList
- Book Price
- Buy Methode
- Promo Methode
- Thankyou
- Pencil Price
- Features

## Cara Kerja 

- Masukkan Teks Pertanyaan 
- Pertanyaan akan dipreprocessing (Remove punctuation, stopword, stemming, vectorizing)
- Hasil preprocessing akan diprediksi
- Hasil prediksi akan di inverse encoding
- Dipilih secara random nilai dari kolom yang diambil dari hasil prediksi

