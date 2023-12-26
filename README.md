# Analisis Sentimen Berbasis Aspek dengan Support Vector Machine dan Word2Vec
Project ini dilakukan untuk mengevaluasi Ulasan Aplikasi Polri Super App dengan mengimplementasikan algoritma *Support Vector Machine* dan *Word2Vec*. Analisis 
dilakukan dengan fokus pada kata kunci dengan persentase terbesar pada setiap aspek, dan kesimpulan dari analisis ini digunakan untuk menilai apakah penelitian telah memenuhi tujuan dan kriteria yang ditetapkan 

## Sumber Data
Data yang digunakan pada penelitian ini bersumber dari ulasan aplikasi Polri Super App di [Google Play](https://github.com/YunicoArdianPradana/Analisis-Sentimen-Berbasis-Aspek-dengan-SVM-dan-Word2Vec/blob/master/Data_Fix.xlsx)
yang berjumlah 2000 data dengan teknik web scrapping. Data tersebut nantinya digunakan sebagai data training sedangkan untuk proses Generalisasi

## Penjelasan File
- /dataset: Direktori berisi dataset yang digunakan pada penelitian ini dengan format csv
- /streamlit: berisi file python dengan nama visualisasi.py untuk menjalankan streamlit
- Proyek_Analisis_Data.ipynb: file ipynb yang digunakan untuk proses Exploratory Data Analysis untuk menjawab berbagai pertanyaan bisnis diatas

## Instalasi
1. Salin repositori ke komputer lokal Anda menggunakan perintah berikut:
   ```shell
   git clone https://github.com/mhaidar10/Submission_Analisis_Data_Python.git
   ```
2. Instalasi dan Konfigurasi Kaggle API:
   [Instalasi Kaggle dan Konfigurasi Kaggle API](https://github.com/Kaggle/kaggle-api).
3. Lakukan instalasi beberapa library yang digunakan pada project ini : pip install pandas streamlit pyplot 
   ```shell
    pip install pandas streamlit pyplot
    ```
   
## Penggunaan
ada 2 cara untuk menjalankan visualisasi streamlit yaitu secara lokal dan secara online di streamlit cloud
1. Melakukan Akses dan Kompilasi(Local):

    ```shell
    cd streamlit
    streamlit run visualisasi.py
    ```
2. akses visualisasi melalui streamlit cloud (Online): 
   [Project Data Analytics](https://yunico-data-analytic.streamlit.app/)

## Kontak
Jika Anda memiliki pertanyaan, hubungi ke email: yunicoardian123@gmail.com

