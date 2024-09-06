# Clustering

_Project ini dibuat guna mengevaluasi pembelajaran khususnya pada konsep Clustering._

---

## Assignment Objectives

*Graded Challenge* ini dibuat guna mengevaluasi konsep Clustering sebagai berikut:

- Mampu memperoleh data menggunakan BigQuery

- Mampu mempersiapkan data untuk digunakan dalam Clustering

- Mampu memahami konsep Clustering dengan menggunakan Scikit-Learn

- Mampu mengimplementasikan Clustering pada data yang ada

---

## Dataset
1. Dataset menggunakan Google BigQuery.
   * Project ID : `ftds-hacktiv8-project`
   
   * Dataset Name : 
     
     +  `phase1_ftds_018_hck`
   
   * Table Name : `credit-card-information`

2. Ambil data dengan bernilai genap : 
   * Semua data dengan column `CUST_ID` bernilai genap.

3. Berikut ini adalah informasi dari setiap column. 
   <img src='https://i.ibb.co/2sbf0Js/P1-G4-Dataset-Information.png'>

4. Menyimpan dataset dalam bentuk `.csv` dengan nama `P1G6_Set_1_banyu_nurmanjaya.csv`.

5. Menyalin query yang telah dibuat di Google Cloud Platform. Telah ditulis pada bagian atas notebook.

6. Menampilkan `10 data pertama` dan `10 data terakhir` dari dataset pada notebook.

---

## Problems

Buatlah model clustering untuk melakukan Customer Segmentation dari data kartu kredit sebuah bank dibawah ini. Data ini merupakan data informasi penggunaan kartu kredit selama 6 bulan terakhir. 

## Assignment with Criteria

1. Machine learning framework yang digunakan adalah *Scikit-Learn*.

2. Adanya penggunaan library visualisasi, seperti *matplotlib*, *seaborn*, atau yang lain.

3. Isi *notebook* mengikuti *outline* di bawah ini:
   1. Perkenalan
      > Bab pengenalan berisi tentang identitas, gambaran besar dataset yang digunakan, dan *objective* yang ingin dicapai.
   
   2. Query SQL
      > Menulis query yang telah dibuat untuk mengambil data dari Google Cloud Platform di bagian ini.

   3. Import Libraries
      > *Cell* pertama pada *notebook* **berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
   
   4. Data Loading
      > Bagian ini berisi proses penyiapan data sebelum dilakukan eksplorasi data lebih lanjut. Proses Data Loading dapat berupa memberi nama baru untuk setiap kolom, mengecek ukuran dataset, dll.
   
   5. Exploratory Data Analysis (EDA)
      > Bagian ini berisi explorasi data pada dataset diatas dengan menggunakan query, grouping, visualisasi sederhana, dan lain sebagainya.
   
   6. Feature Engineering
      > Bagian ini berisi proses penyiapan data untuk proses pelatihan model, seperti transformasi data (normalisasi, encoding, dll.), dan proses-proses lain yang dibutuhkan.
   
   7. Model Definition
      > Bagian ini berisi cell untuk mendefinisikan model. Jelaskan alasan menggunakan suatu algoritma/model, hyperparameter yang dipakai, jenis penggunaan metrics yang dipakai, dan hal lain yang terkait dengan model.

   8. Model Training
      > Cell pada bagian ini hanya berisi code untuk melatih model dan output yang dihasilkan. Melakukan beberapa kali proses training dengan hyperparameter yang berbeda untuk melihat hasil yang didapatkan. Analisis dan narasikan hasil ini pada bagian Model Evaluation.
   
   9. Model Evaluation
      > Pada bagian ini, dilakukan evaluasi model yang menunjukkan bagaimana performa model berdasarkan metrics yang dipilih. Hal ini dibuktikan dengan visualisasi tren performa dan/atau tingkat kesalahan model. **Lakukan analisis terkait dengan hasil pada model dan tuliskan hasil analisisnya**.

   10. Model Saving
       > Pada bagian ini, dilakukan proses penyimpanan model dan file-file lain yang terkait dengan hasil proses pembuatan model.

   11. Model Inference
       > Model yang sudah dilatih akan dicoba pada data yang bukan termasuk ke dalam train-set. Data ini dalam format yang asli, bukan data yang sudah di-scaled.
   
   12. Pengambilan Kesimpulan
       > Pada bagian terakhir ini, ** berisi** kesimpulan yang mencerminkan hasil yang didapat dengan *objective* yang sudah ditulis di bagian pengenalan.
    
