# Perbandingan Model Regresi terhadap Tahun Produksi dan Harga Mobil
-------
# DESKRIPSI 


Proyek ini bertujuan untuk menganalisis hubungan antara tahun produksi mobil dan harga mobil di Nigeria. Penelitian ini menerapkan tiga model regresi yang berbeda yaitu Regresi Linear, Metode LOESS, dan Regresi Robust—untuk menentukan model mana yang paling tepat dalam memprediksi data. Fokus utama penelitian ini adalah mengevaluasi efektivitas setiap model dalam menangani outlier serta inkonsistensi data, sehingga dapat memberikan prediksi harga mobil yang lebih akurat berdasarkan tahun produksinya.

# TUJUAN 
1. Menganalisis keterkaitan antara tahun produksi mobil dengan harga jualnya.
2. Mengevaluasi kelebihan dan kelemahan dari beberapa metode regresi, yaitu Linear, LOESS, dan Robust.
3. Menentukan model regresi yang paling cocok untuk dataset dan mampu memberikan prediksi yang tepat, terutama saat terdapat outlier dalam data dan inkonsistensi data.

# ALUR KERJA 
1. Pengumpulan Data:

   - Dataset yang digunakan dalam proyek ini diambil dari pasar online di Nigeria yang menghubungkan penjual dan pembeli mobil bekas. Dataset ini mencakup informasi seperti merk mobil, tahun produksi, kondisi, ukuran mesin, jarak tempuh, harga, dan faktor lainnya.
2. Pre-Processing Data:

   - Pembersihan Data: Menghapus nilai yang hilang dan kolom yang tidak memiliki cukup data.
   - Reduksi Data: Mengurangi dataset ke fitur-fitur yang relevan untuk analisis.
   - Analisis Data Eksploratif (EDA): Melakukan analisis korelasi dan visualisasi scatterplot untuk mengeksplorasi hubungan awal antar variabel.
3. Model Regresi:

   - Regresi Linear: Menggunakan regresi linear sederhana untuk memodelkan hubungan antara tahun produksi mobil dan harga.
   - Metode LOESS: Metode smoothing LOESS diterapkan untuk menangani hubungan non-linear dan outlier dalam data.
   - Regresi Robust: Dirancang untuk menangani outlier, memberikan hasil regresi yang stabil meskipun terdapat data abnormal.
4. Evaluasi Model:

   - Performa setiap model regresi dievaluasi berdasarkan Residual Standard Error (RSE), R-squared, Mean Squared Error (MSE), Standard Error dan kemampuannya dalam menangani outlier.

# KESIMPULAN 
Setiap metode regresi memiliki kelebihan dan kekurangan:

- Regresi Linear: Efisien tetapi kurang ideal dalam menangani outlier atau data yang tidak linear.
- Metode LOESS: Memberikan prediksi yang paling akurat, terutama di hadapan outlier, karena kemampuannya untuk melakukan smoothing lokal pada data.
- Regresi Robust: Efektif dalam menangani dataset dengan outlier, meskipun sedikit kurang akurat dalam prediksi keseluruhan dibandingkan dengan LOESS.

---------
# Tim 

- Sherryl Kurniawan 
- Rasyad Muhammad Ramdhanazuri
- Dira Abiyyu Baaspati
- Reyza Rahmatsyah 


