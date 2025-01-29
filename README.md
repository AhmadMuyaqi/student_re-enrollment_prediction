# Prediksi Heregistrasi Calon Mahasiswa Baru dengan Random Forest

## Deskripsi Proyek
Sistem ini dikembangkan untuk memprediksi heregistrasi calon mahasiswa baru di Universitas Selamat Sri Batang menggunakan algoritma Random Forest. Model yang dibangun membantu pihak pengelola universitas dalam mengidentifikasi calon mahasiswa yang berpotensi tidak melakukan heregistrasi.

## Tujuan
- Mengembangkan model klasifikasi untuk memprediksi status heregistrasi mahasiswa baru.
- Menganalisis faktor-faktor yang mempengaruhi heregistrasi mahasiswa.

## Teknologi yang Digunakan
- **Python**: Bahasa pemrograman utama.
- **Flask**: Framework web untuk menampilkan hasil prediksi.
- **Random Forest**: Algoritma utama untuk klasifikasi.
- **SMOTE**: Untuk menangani ketidakseimbangan data.
- **Chi-Square**: Untuk seleksi fitur terbaik.
- **Scikit-learn**: Untuk implementasi machine learning.
- **Pandas & NumPy**: Untuk manipulasi data.

## Fitur Utama
- **Prediksi Heregistrasi**: Model dapat memprediksi apakah calon mahasiswa akan melakukan heregistrasi atau tidak.
- **Preprocessing Data**: Pembersihan dan transformasi data sebelum modelling.
- **Balancing Data**: Menggunakan SMOTE untuk mengatasi ketidakseimbangan data.
- **Seleksi Fitur**: Menggunakan Chi-Square untuk memilih fitur yang paling berpengaruh.
- **Evaluasi Model**: Menggunakan confusion matrix, accuracy, precision, dan recall.

## Instalasi dan Penggunaan
1. **Clone Repository**
   ```bash
   git clone https://github.com/username/heregistrasi-prediction.git
   cd heregistrasi-prediction
   ```
2. **Instalasi Dependensi**
   ```bash
   pip install -r requirements.txt
   ```
3. **Menjalankan Aplikasi**
   ```bash
   python app.py
   ```
4. **Menggunakan Ngrok untuk Akses Publik**
   ```bash
   ngrok http 5000
   ```
5. **Akses Aplikasi**
   Buka browser dan akses `http://127.0.0.1:5000` atau gunakan URL dari Ngrok.

## Dataset
Dataset yang digunakan adalah data penerimaan mahasiswa baru Universitas Selamat Sri Batang tahun akademik 2020 hingga 2023 dengan total **1.358 data**, terdiri dari **12 atribut** dan **1 kelas target**.

## Evaluasi Model
- **Akurasi Model**: 93,76% setelah balancing dengan SMOTE dan seleksi fitur dengan Chi-Square.
- **Confusion Matrix**: Digunakan untuk mengevaluasi prediksi model.
- **Metode Evaluasi**: Precision, Recall, dan F1-Score.

## Pengembang
**Ahmad Muyaqi**  
Program Studi Pendidikan Teknik Informatika dan Komputer  
Universitas Negeri Semarang

## Kontak
Jika ada pertanyaan atau saran, silakan hubungi melalui email: muyaqiahmad@gmail.com atau kunjungi LinkedIn https://www.linkedin.com/in/ahmadmuyaqi/.

