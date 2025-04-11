# Proyek Analisis Sentimen - BPML Submission

## Deskripsi Proyek
Proyek ini merupakan bagian dari submission akhir program **BPML (Belajar Pengembangan Machine Learning )**. Fokus utama proyek ini adalah **klasifikasi teks** menggunakan beberapa algoritma machine learning dan deep learning, di antaranya:

- **Support Vector Machine (SVM)**
- **Convolutional Neural Network (CNN)**
- **Long Short-Term Memory (LSTM)**
- **Gated Recurrent Unit (GRU)**

Model dilatih menggunakan dataset teks dan dievaluasi berdasarkan akurasi pada data latih dan uji.

## Struktur Proyek

- **README.md**  
  File ini yang menjelaskan isi dan struktur proyek.

## Teknologi yang Digunakan
- Python 3
- Pandas untuk manipulasi data
- NumPy untuk perhitungan numerik
- Scikit-learn untuk algoritma SVM dan metrik evaluasi
- TensorFlow & Keras untuk model deep learning (CNN, LSTM, GRU)
- Matplotlib & Seaborn untuk visualisasi data

## Cara Penggunaan

### Menjalankan Virtual Environment (venv)
1. Buat virtual environment baru:
   ```bash
   python -m venv venv
   ```

2. Aktifkan virtual environment:
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```

3. Install semua dependensi yang dibutuhkan:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
   ```

### Menjalankan Jupyter Notebook
1. Jalankan perintah berikut untuk membuka Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Buka file.

3. Jalankan setiap sel secara berurutan untuk melihat proses preprocessing, pelatihan model, dan evaluasi hasil.

