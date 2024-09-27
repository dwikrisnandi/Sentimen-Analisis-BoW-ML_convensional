
# Analisis Sentimen Ulasan BRIMO Menggunakan Bag of Words (BoW)

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis sentimen pada ulasan aplikasi BRIMO. Ulasan-ulasan ini akan diproses menggunakan teknik **Bag of Words (BoW)** untuk membangun model sentimen yang dapat memprediksi apakah ulasan bersifat positif atau negatif.

## Dataset
Dataset yang digunakan adalah kumpulan ulasan aplikasi BRIMO yang telah disimpan dalam file `ulasan_brimo.csv`. Data ini diambil dari hasil scraping ulasan pengguna aplikasi BRIMO di dile `Analisis_Sentimen_Scarping`.

## Prasyarat
Proyek ini menggunakan beberapa pustaka Python yang harus diinstal sebelum menjalankan kode:
- pandas
- numpy
- nltk
- matplotlib
- seaborn
- wordcloud
- sastrawi

Anda dapat menginstal semua pustaka yang diperlukan dengan perintah berikut:
```bash
pip install pandas numpy matplotlib seaborn wordcloud sastrawi nltk
```

## Cara Menjalankan
1. Download atau clone repository ini.
2. Pastikan Anda memiliki dataset `ulasan_brimo.csv` yang atay menjalanjan
   ```bash
   Analisis_sentimen_Scraping.ipynb
   ```
4. Jalankan script Python untuk memproses data dan melakukan analisis sentimen.
   ```bash
   Analisis_sentimen_BoW.ipynb
   ```

## Model yang Digunakan
Proyek ini menggunakan pendekatan **Bag of Words (BoW)** untuk mewakili teks dalam bentuk vektor yang kemudian digunakan untuk memprediksi sentimen ulasan.

Selain itu, digunakan juga beberapa teknik pemrosesan teks, seperti:
- Tokenisasi dengan `nltk`
- Stemming dan penghapusan kata-kata berhenti menggunakan pustaka `Sastrawi` (Bahasa Indonesia)
- Visualisasi data dengan `matplotlib` dan `seaborn`
- WordCloud untuk visualisasi kata-kata yang paling sering muncul dalam ulasan

## Hasil Akhir
Hasil dari analisis ini adalah prediksi apakah suatu ulasan bersifat positif atau negatif, serta berbagai visualisasi data ulasan yang telah diproses.

## Penulis

**DWI KRISNANDI**

Silakan hubungi jika memiliki pertanyaan atau membutuhkan bantuan lebih lanjut.
