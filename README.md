# Analisis Sentimen Berbasis Aspek dengan Support Vector Machine dan Word2Vec
Project ini dilakukan untuk mengevaluasi Ulasan Aplikasi Polri Super App dengan mengimplementasikan algoritma *Support Vector Machine* dan *Word2Vec*. Analisis 
dilakukan dengan fokus pada kata kunci dengan persentase terbesar pada setiap aspek, dan kesimpulan dari analisis ini digunakan untuk menilai apakah penelitian telah memenuhi tujuan dan kriteria yang ditetapkan 

## Batasan Peneltian
1. Aspek yang digunakan adalah layanan, sistem dan kebermanfaatan
2. Data diklasifikasikan kedalam sentimen positif dan negatif

## Tahapan Penelitian
![image](https://github.com/YunicoArdianPradana/Analisis-Sentimen-Berbasis-Aspek-dengan-SVM-dan-Word2Vec/blob/master/Diagram%20Alir%20Penelitian.png)

## Sumber Data
Data yang digunakan pada penelitian ini bersumber dari ulasan aplikasi Polri Super App di [Google Play](https://github.com/YunicoArdianPradana/Analisis-Sentimen-Berbasis-Aspek-dengan-SVM-dan-Word2Vec/blob/master/Data_Fix.xlsx)
yang berjumlah 2000 data dengan teknik web scrapping. Data tersebut nantinya digunakan sebagai data training sedangkan untuk proses Generalisasi menggunakan [data generate](https://github.com/YunicoArdianPradana/Analisis-Sentimen-Berbasis-Aspek-dengan-SVM-dan-Word2Vec/blob/master/Data%20Generate%201000.xlsx) sejumlah 1000 data untuk mengetahui kemampuan algoritma SVM dalam klasifikasi sentimen dan aspek.

## Penjelasan File
- AnalisisSentimen.ipynb: File python yang digunakan untuk proses analisis sentimen 
- Data Generate 1000.xlsx: Data yang digunakan untuk proses generalisasi data
- Data_Fix.xlsx: Data yang digunakan untuk proses training 

## Kontak
Jika Anda memiliki pertanyaan, hubungi ke email: yunicoardian123@gmail.com

