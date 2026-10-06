# Klasifikasi-Tingkat-Risiko-Sampah-Plastik-di-Kawasan-Pesisir-Menggunakan-Random-Forest

## Latar Belakang
Sampah laut merupakan salah satu masalah yang dapat mengganggu kelestarian ekosistem laut. Sampah seperti plastik, botol, dan berbagai jenis limbah lainnya dapat mencemari perairan serta membahayakan kehidupan biota laut. Karena itu, diperlukan upaya untuk mengetahui dan mengelompokkan tingkat pencemaran sampah laut agar penanganannya dapat dilakukan dengan lebih tepat.

## Tujuan Projek

    1. Mengidentifikasi kondisi pencemaran sampah laut berdasarkan data yang tersedia.
    2. Mengklasifikasikan tingkat pencemaran menjadi kategori rendah, sedang, dan tinggi.
    3. Menerapkan metode Random Forest untuk melakukan klasifikasi.
    4. Membandingkan hasil Random Forest dengan Logistic Regression.
    5. Mengetahui fitur yang paling banyak berkontribusi terhadap hasil klasifikasi.
    
## Rumusan Masalah
    1. Bagaimana cara menentukan tingkat pencemaran sampah laut berdasarkan data yang tersedia?
    2. Bagaimana cara mengelompokkan tingkat pencemaran menjadi rendah, sedang, dan tinggi?
    3. Bagaimana Random Forest dapat digunakan untuk mengklasifikasikan tingkat pencemaran sampah laut?

## Dataset
Nama Dataset : Global Plastic Waste 2023: Country-wise Data

Sumber : Kaggle

Jumlah data awal: 164 data

Jumlah kolom: 6

## Tahapan Penelitian
- Membaca Dataset dan Data Understanding
- Data Cleaning dan Preprocessing
- Menentukan Fitur dan Target
- Membagi Data Training dan Testing
- Preprocessing Data
- Pemodelan Random Forest
- Pemodelan Logistic Regression
- Evaluasi Model
- Confusion Matrix
- Feature Importance

# Algoritma yang Digunakan
## Random Forest 
digunakan sebagai algoritma utama untuk mengklasifikasikan tingkat risiko sampah plastik menjadi Low, Medium, dan High.

## Logistic Regression
digunakan sebagai algoritma pembanding untuk melihat perbedaan performa dengan Random Forest.

## Hasil dan Evaluasi
Evaluasi dilakukan menggunakan Accuracy, Precision, Recall, dan F1-Score.

Hasil pengujian menunjukkan bahwa Random Forest memperoleh akurasi sebesar 66,67%, sedangkan Logistic Regression memperoleh akurasi sebesar 54,55%.

| Model | Accuracy |
|---|---:|
| Random Forest | 66,67% |
| Logistic Regression | 54,55% |

Berdasarkan hasil tersebut, Random Forest memiliki performa yang lebih baik dibandingkan Logistic Regression pada dataset yang digunakan.

## Kesimpulan
1. Dataset berhasil digunakan untuk mengklasifikasikan
   tingkat risiko sampah plastik menjadi tiga kategori,
   yaitu Low, Medium, dan High.

2. Random Forest dan Logistic Regression berhasil
   diterapkan untuk melakukan klasifikasi.

3. Hasil evaluasi digunakan untuk mengetahui model
   yang memberikan performa lebih baik.

4. Feature Importance digunakan untuk mengetahui
   fitur yang paling banyak berkontribusi terhadap
   prediksi model.

5. Hasil klasifikasi dapat menjadi informasi tambahan
   dalam memahami kondisi pencemaran sampah di kawasan
   pesisir.

## Teknologi yang Digunakan
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
