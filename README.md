# Ujian-LSP (Analisis Prediksi Mortalitas Pasien Gagal Jantung: Perbandingan Model dengan Dua Fitur Kunci vs Seluruh Fitur Klinis)

## Latar Belakang Masalah
Kesehatan adalah pilar utama kehidupan. Salah satu ancaman serius yang dihadapi masyarakat saat ini adalah **gagal jantung**, penyakit kronis yang menjadi penyebab utama kematian di seluruh dunia. Gagal jantung terjadi ketika jantung tidak mampu memompa darah yang cukup untuk memenuhi kebutuhan tubuh, yang sering kali berujung pada komplikasi yang mengancam jiwa.

Menyadari pentingnya penanganan dini dan akurat terhadap penyakit ini, dunia medis dan teknologi bekerja sama untuk menghadirkan solusi berbasis data. Salah satu langkah penting adalah pemanfaatan dataset medis untuk membangun model prediksi yang dapat membantu dokter dan tenaga medis dalam mengidentifikasi pasien berisiko tinggi.

Dataset **Heart Failure Clinical Records**, yang terdiri dari 299 catatan medis pasien gagal jantung, menyediakan data penting yang mencakup berbagai faktor seperti `age`, `anaemia`, `creatinine_phosphokinase`, `diabetes`, `ejection_fraction`, `high_blood_pressure`, `platelets`, `serum_creatinine`, `serum_sodium`, `sex`, `smoking`, `time`, `death_event`. Informasi ini menjadi fondasi untuk mengembangkan model prediktif yang akurat.

## Tujuan Ujian Sertifikasi
Tujuan utama dari analisis dataset ini adalah:
1. **Mengidentifikasi variabel kunci** yang memengaruhi risiko mortalitas pasien gagal jantung.
2. **Membangun model prediktif** yang dapat membantu memprediksi kelangsungan hidup pasien gagal jantung.

Dengan hasil analisis ini, diharapkan dataset dapat memberikan wawasan yang berharga kepada rumah sakit, tenaga medis, dan pembuat kebijakan dalam mengurangi angka kematian akibat gagal jantung.

## Terkait Dataset
- **Sumber Data**: [Heart Failure Clinical Records Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records)
- **Jumlah Sampel Data**: 299 pasien
- **Jumlah Atribut**: 13 atribut, meliputi: `age`, `anaemia`, `creatinine_phosphokinase`, `diabetes`, dan lainnya.
- **Label**: Kematian pasien selama periode tindak lanjut (0 = hidup, 1 = meninggal).

## Pendekatan Analisis
Untuk mendukung analisis dataset ini, akan dibuat skema komparasi model prediksi yang dilakukan dengan dua pendekatan berbeda:

1. **Menggunakan Dua Fitur Penting**: Model akan dibangun hanya dengan menggunakan dua fitur kunci, yaitu `serum_creatinine` dan `ejection_fraction`. Kedua fitur ini dipilih karena memiliki hubungan signifikan dengan fungsi ginjal dan keseimbangan elektrolit yang berdampak pada kondisi gagal jantung.

2. **Menggunakan Semua Fitur**: Model akan dibangun dengan memanfaatkan semua 13 fitur yang tersedia dalam dataset untuk melihat seberapa besar peningkatan akurasi dan performa jika semua informasi digunakan.

Studi ini berfokus pada dataset 299 pasien yang dikumpulkan pada tahun 2015 untuk mengevaluasi apakah dua faktor klinis utama **serum creatinine** dan **ejection fraction** cukup, untuk memprediksi kelangsungan hidup pasien dengan lebih akurat dibandingkan menggunakan seluruh data fitur klinis.


