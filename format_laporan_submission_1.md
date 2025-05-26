# Laporan Proyek Machine Learning - Nama Anda

## Domain Proyek

## Domain Proyek

Sepeda motor merupakan salah satu moda transportasi utama di Indonesia karena harganya yang terjangkau, efisiensi bahan bakar, dan fleksibilitas dalam menghadapi kemacetan. Karena harga motor baru terus meningkat, banyak masyarakat beralih ke pasar motor bekas sebagai solusi yang lebih ekonomis. Namun demikian, penentuan harga motor bekas sering kali tidak konsisten karena dipengaruhi oleh banyak variabel seperti merk, tahun pembuatan, jarak tempuh, tipe varian, serta kondisi dokumen resmi seperti STNK dan BPKB.

Ketidakpastian dalam menentukan harga motor bekas ini menjadi tantangan bagi konsumen maupun penjual. Konsumen kesulitan membandingkan harga yang wajar untuk motor dengan kondisi tertentu, sementara penjual berisiko memberikan harga yang tidak kompetitif di pasar. Oleh karena itu, perusahaan dan platform jual beli motor bekas perlu membangun sistem prediksi harga yang akurat dan objektif. Model prediktif berbasis machine learning mampu mengolah pola dari data historis dan fitur kendaraan untuk memberikan estimasi harga yang lebih masuk akal.

Beberapa penelitian telah menunjukkan bahwa pendekatan machine learning efektif dalam memprediksi harga kendaraan. Misalnya, studi oleh Putra *et al.* \[1] menunjukkan bahwa model seperti Random Forest, Decision Tree, dan Gradient Boosting mampu menghasilkan akurasi tinggi dalam prediksi harga mobil bekas, dengan Random Forest menjadi model paling unggul berdasarkan nilai R² dan MAE. Di sisi lain, laporan dari OLX Autos dan MarkPlus, Inc. \[2] juga mengungkap bahwa transparansi harga merupakan faktor kunci dalam kepercayaan konsumen terhadap transaksi kendaraan bekas. Oleh sebab itu, model prediksi harga motor bekas sangat relevan untuk meningkatkan efisiensi pasar dan pengalaman pengguna.

**Referensi**:

\[1] P. H. Putra, B. P. Azanuddin, dan Y. A. Dalimunthe, "Random forest and decision tree algorithms for car price prediction," *Jurnal Matematika Dan Ilmu Pengetahuan Alam LLDikti Wilayah 1 (JUMPA)*, vol. 3, no. 2, pp. 81–89, 2023. \[Online]. Tersedia: [https://www.researchgate.net/publication/370343508](https://www.researchgate.net/publication/370343508)

\[2] OLX Autos & MarkPlus, Inc., "Consumer Behavior Report: Used Car Market in Indonesia," 2021.


**Rubrik/Kriteria Tambahan (Opsional)**:
- Jelaskan mengapa dan bagaimana masalah tersebut harus diselesaikan
- Menyertakan hasil riset terkait atau referensi. Referensi yang diberikan harus berasal dari sumber yang kredibel dan author yang jelas.
- Format Referensi dapat mengacu pada penulisan sitasi [IEEE](https://journals.ieeeauthorcenter.ieee.org/wp-content/uploads/sites/7/IEEE_Reference_Guide.pdf), [APA](https://www.mendeley.com/guides/apa-citation-guide/) atau secara umum seperti [di sini](https://penerbitdeepublish.com/menulis-buku-membuat-sitasi-dengan-mudah/)
- Sumber yang bisa digunakan [Scholar](https://scholar.google.com/)

## Business Understanding

Pada bagian ini, kamu perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Pernyataan Masalah 1
- Pernyataan Masalah 2
- Pernyataan Masalah n

### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

    ### Solution statements
    - Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
    - Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

### Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.

