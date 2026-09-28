# Analisis Cuaca Sulawesi Tenggara & Prediksi Hujan

Proyek ini membangun model *supervised binary classification* untuk memprediksi
hujan atau tidak hujan berdasarkan data cuaca harian Sulawesi Tenggara.
Model dilatih menggunakan data BMKG periode 2022–2023 dan diintegrasikan
ke dalam aplikasi web interaktif berbasis Streamlit.


## Latar Belakang

Sulawesi Tenggara termasuk wilayah tropis dengan curah hujan tinggi dan tidak menentu. Perubahan iklim membuat pola hujan makin sulit diprediksi, sehingga petani, nelayan, dan masyarakat umum sering salah mengambil keputusan — mulai dari waktu tanam, waktu melaut, hingga kesiapan menghadapi cuaca ekstrem.

Proyek ini mendukung **SDGS 13: Penanganan Perubahan Iklim**, ) Model ini bukan solusi langsung untuk menghentikan perubahan iklim, melainkan alat bantu kesiapsiagaan berbasis data.

Sebagai solusi, proyek ini membangun model machine learning yang memprediksi hujan atau tidak hujan berdasarkan data cuaca harian, lalu diintegrasikan ke aplikasi web interaktif agar siapa pun bisa menggunakannya dengan mudah.





## 📊 Dataset

- **Sumber:** Data cuaca harian Sulawesi Tenggara
- **Periode:** 1 Januari 2022 - November 2023
- **Jumlah:** 699 baris, 8 kolom
- **Fitur:** Tanggal, Suhu min/max/ata-rata, Kelembapan, Curah hujan, Penyinaran matahari, Kecepatan angin

## ⚙️ Metode

Proyek ini dilakukan melalui beberapa tahapan, yaitu:

1. **Pengumpulan Data**  
   Menggunakan dataset cuaca harian Sulawesi Tenggara periode 1 Januari 2022 hingga November 2023.

2. **Preprocessing Data**  
   Melakukan pemeriksaan dan pembersihan data, seperti menangani nilai kosong, memperbaiki format data, serta menyesuaikan nilai yang tidak valid agar dataset siap digunakan.

3. **Eksplorasi Data**  
   Menganalisis karakteristik dataset melalui statistik deskriptif dan visualisasi untuk memahami pola serta hubungan antarvariabel cuaca.

4. **Persiapan Data**  
   Menentukan fitur yang digunakan sebagai variabel input dan mengelompokkan kondisi cuaca menjadi dua kategori, yaitu hujan dan tidak hujan.

5. **Pemodelan Machine Learning**  
   Melatih model klasifikasi menggunakan data cuaca yang telah diproses untuk mempelajari pola yang berkaitan dengan kejadian hujan.

6. **Evaluasi Model**  
   Mengukur kinerja model menggunakan metrik evaluasi klasifikasi untuk mengetahui kemampuan model dalam memprediksi kondisi hujan dan tidak hujan.

7. **Prediksi**  
   Menggunakan model yang telah dilatih untuk memprediksi kemungkinan kondisi hujan berdasarkan data parameter cuaca yang diberikan.

## 📁 Struktur Project

