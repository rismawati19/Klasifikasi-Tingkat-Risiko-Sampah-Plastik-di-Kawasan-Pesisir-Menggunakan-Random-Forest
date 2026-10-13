# Klasifikasi Tingkat Risiko Sampah Plastik di Kawasan Pesisir

## Tentang Proyek

Proyek ini dibuat untuk menerapkan Machine Learning dalam mengklasifikasikan tingkat risiko sampah plastik di kawasan pesisir. Sampah plastik merupakan salah satu masalah lingkungan yang dapat mengganggu kelestarian ekosistem laut. Oleh karena itu, diperlukan analisis data untuk membantu memahami kondisi dan tingkat risiko sampah plastik.

Pada proyek ini, metode **Random Forest** digunakan sebagai model utama, sedangkan **Logistic Regression** digunakan sebagai model pembanding. Hasil klasifikasi diharapkan dapat menjadi informasi tambahan dalam memahami risiko sampah plastik di kawasan pesisir.

## Tujuan Proyek

1. Menganalisis dataset yang berkaitan dengan sampah plastik.
2. Mengklasifikasikan tingkat risiko sampah plastik menjadi kategori rendah, sedang, dan tinggi.
3. Menerapkan algoritma Random Forest untuk melakukan klasifikasi.
4. Membandingkan performa Random Forest dengan Logistic Regression.
5. Mengetahui fitur yang berkontribusi terhadap hasil klasifikasi menggunakan Feature Importance.

## Dataset

Dataset yang digunakan dalam proyek ini adalah `Plastic_Waste_Around_the_World_Rapih (1).csv`.

Beberapa fitur yang digunakan dalam proses klasifikasi meliputi:

- `Total_Plastic_Waste_MT`: jumlah total sampah plastik dalam satuan metrik ton.
- `Recycling_Rate`: tingkat daur ulang sampah plastik.
- `Per_Capita_Waste_KG`: jumlah sampah per kapita dalam kilogram.
- `Main_Sources`: sumber utama sampah plastik.

Target klasifikasi terdiri dari tiga kategori:

- **Low**: risiko rendah.
- **Medium**: risiko sedang.
- **High**: risiko tinggi.

Kategori `Very_High` dikeluarkan dari data sebelum proses pemodelan dilakukan.

## Metode yang Digunakan

Proyek ini dilakukan melalui beberapa tahapan:

1. **Data Understanding** — membaca dataset dan memeriksa struktur, data kosong, serta data duplikat.
2. **Data Cleaning dan Preprocessing** — menyiapkan data dan mengubah fitur kategori menggunakan One-Hot Encoding.
3. **Pembagian Data** — membagi data menjadi 80% data training dan 20% data testing.
4. **Pemodelan Random Forest** — melatih model utama untuk memprediksi tingkat risiko sampah plastik.
5. **Pemodelan Logistic Regression** — membuat model pembanding.
6. **Evaluasi Model** — mengevaluasi hasil menggunakan accuracy, precision, recall, dan F1-score.
7. **Confusion Matrix** — melihat hasil prediksi yang benar dan salah pada setiap kategori.
8. **Feature Importance** — mengetahui fitur yang paling berkontribusi terhadap prediksi Random Forest.

## Teknologi yang Digunakan

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

## Struktur File

- `Klasifikasi_Tingkat_Resiko_Sampah_Plastik_di_Kawasan_Pesisir.ipynb` — notebook berisi tahapan analisis dan pemodelan.
- `klasifikasi_tingkat_resiko_sampah_plastik_di_kawasan_pesisir.py` — file kode Python untuk proyek.
- `Plastic_Waste_Around_the_World_Rapih (1).csv` — dataset yang digunakan.
- `Klasifikasi_Tingkat_Risiko_Sampah_Plastik_Pesisir_kel_5.pptx` — materi presentasi proyek.
- `README.md` — dokumentasi proyek.

## Cara Menjalankan Proyek

1. Unduh atau clone repository ini.
2. Pastikan Python dan library yang dibutuhkan sudah tersedia.
3. Buka file notebook menggunakan Jupyter Notebook atau Google Colab.
4. Pastikan dataset CSV tersedia di lokasi yang sesuai dengan kode.
5. Jalankan setiap sel notebook secara berurutan untuk melakukan analisis, pelatihan model, evaluasi, dan visualisasi hasil.

Untuk memasang library yang dibutuhkan, jalankan perintah berikut:

```bash
pip install pandas scikit-learn matplotlib jupyter
```

## Hasil dan Kesimpulan

Proyek ini menerapkan dua algoritma Machine Learning, yaitu Random Forest dan Logistic Regression, untuk mengklasifikasikan tingkat risiko sampah plastik menjadi kategori rendah, sedang, dan tinggi. Evaluasi model dilakukan untuk membandingkan performa kedua algoritma, sedangkan Confusion Matrix dan Feature Importance digunakan untuk membantu memahami hasil klasifikasi.

Hasil proyek ini diharapkan dapat memberikan gambaran mengenai penerapan Machine Learning dalam analisis risiko sampah plastik. Namun, hasil klasifikasi tetap bergantung pada kualitas dataset dan performa model yang diperoleh.

## Tujuan Pembangunan Berkelanjutan

Proyek ini berkaitan dengan **Sustainable Development Goal (SDG) 14: Life Below Water**, yang berfokus pada pelestarian dan pemanfaatan sumber daya laut secara berkelanjutan.

Melalui analisis data dan penerapan Machine Learning, proyek ini diharapkan dapat mendukung pemahaman terhadap permasalahan sampah plastik dan pentingnya menjaga kelestarian ekosistem laut.

---

**Catatan:** Proyek ini dibuat untuk keperluan pembelajaran dan penerapan Machine Learning pada analisis lingkungan.
