
<div align="center">
  <a href="https://github.com/jejejery/IF5153-Tugas-Besar-Analisis-Promo">
    <img src="https://static.vecteezy.com/system/resources/previews/042/148/611/non_2x/new-twitter-x-logo-twitter-icon-x-social-media-icon-free-png.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Analisis Promosi di X dengan Pemrosesan Bahasa Alami </h3>

  <p align="center">
    Klasifikasi Teks, <i>Clustering</i>, dan <i>Named-Entity Recognition</i>
    <br />
    <br />
  </p>
</div>

# Deskripsi Sistem
Di era digital yang dipenuhi informasi, sistem inovatif ini hadir sebagai solusi cerdas untuk menavigasi konten promosi di platform X (Twitter). Sistem ini mampu **mengklasifikasikan** konten promosi, mengelompokkannya ke dalam kategori yang spesifik seperti makanan, kesehatan dan kecantikan atau lainnya. Setelah itu, mengekstrak informasi penting seperti produk, lokasi, platform dan lainnya dengan bantuan sistem *Named-entity recognition*. Hal ini dapat menggunakan pengguna untuk dengan cepat menemukan promosi yang relevan dengan minat mereka, tanpa harus terganggu oleh spam atau konten yang tidak relevan.

# Requirement
Library yang dibutuhkan pada program ini antara lain:
* Pandas
* Numpy
* Scikit-Learn
* Scipy
* Transformers
* Sentence Transformers
* Dataset

# Hasil

Berdasarkan *NLP pipeline* yang berhasil dibuat, berikut merupakan performa masing-masing task berdasarkan evaluasi terhadap dataset uji/*test set*:

### Promo/Non-Promo Classification
|Metrik|Nilai|
|----|----|
|Accuracy|0.98|
|F1 Score|0.98|
|Precision|0.98|
|Recall|0.98|

### Promo Category Classification
|Metrik|Nilai|
|----|----|
|Accuracy|0.83|
|F1 Score|0.82|
|Precision|0.83|
|Recall|0.82|

### Promo Category Clustering
|Metrik|Nilai|
|----|----|
|Jumlah cluster optimal (k)|7|
|PCA Embedding Dimension Reduction|15|
|Silhouette Score|0.57|
|Sum of Squared Error|10000|

### Named-Entity Recognition
|Metrik|Nilai|
|----|----|
|F1 Score|0.82|
|Precision|0.83|
|Recall|0.82|

<br/>

# Room for Improvement
- Pemahaman domain promosi yang lebih komprehensif
- Melakukan eksperimen dengan model lain
- Meningkatkan variasi dan kuantitas dataset karena dataset yang digunakan masih sedikit



# Anggota & Pembagian Tugas

|Nama|Kontak|Github|Pembagian Tugas|
|----|-------|------|------|
|Husnia Munzayana | 13521077@std.stei.itb.ac.id|<a href="https://github.com/munzayanahusn">@munzayanahusn</a>| Klasifikasi Promo/Non-promo|
|Shelma Salsabila | 13521115@std.stei.itb.ac.id|<a href="https://www.github.com/shelmasalsa17">@shelmasalsa17</a>| Klasifikasi Kategori Promo|
|Jeremya Dharmawan Raharjo | 13521131@std.stei.itb.ac.id|<a href="https://www.github.com/jejejery">@jejejery</a>| Clustering Kategori Promo & Named-entity recognition untuk aspek promosi|

