# Pelatihan Model Klasifikasi Sentimen Ulasan App Twitter

Repositori ini berisi notebook untuk pelatihan model klasifikasi sentimen menggunakan dataset ulasan aplikasi yang diambil dari Twitter. Notebook ini mencakup proses dari mulai pemuatan data, pembersihan, eksplorasi, preprocessing teks, hingga pelatihan dan evaluasi model machine learning.

## Daftar Isi

- [Deskripsi Proyek](#deskripsi-proyek)
- [Struktur Proyek](#struktur-proyek)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Model yang Digunakan](#model-yang-digunakan)
- [Evaluasi](#evaluasi)
- [Hasil](#hasil)
- [Lisensi](#lisensi)

---

## Deskripsi Proyek

Proyek ini bertujuan membangun model machine learning untuk mengklasifikasikan sentimen (positif, negatif, netral) pada ulasan aplikasi berbasis data Twitter menggunakan berbagai teknik preprocessing dan beberapa algoritma machine learning. Model yang telah dilatih dapat digunakan untuk mengklasifikasikan data baru terkait sentimen ulasan aplikasi.

## Struktur Proyek


## Instalasi

1. **Clone repositori ini:**
    ```bash
    git clone <URL-repo>
    cd <nama-folder>
    ```

2. **Install dependencies:**
    Pastikan sudah menginstall Python 3.x dan pip. Install library berikut:
    ```bash
    pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud sastrawi
    ```

3. **Download NLTK Resource:**
    Resource ini otomatis didownload pada awal notebook. Jika perlu manual:
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    ```

## Penggunaan

1. Jalankan notebook `Pelatihan_model.ipynb` menggunakan Jupyter Notebook/Lab atau Google Colab.
2. Pastikan file dataset `ulasan_app_twitter.csv` berada di path yang sama atau update path-nya.
3. Ikuti langkah-langkah di dalam notebook dari atas ke bawah:
    - **Import Library**
    - **Memuat Dataset**
    - **Data Preprocessing & EDA**
    - **Text Processing**
    - **Feature Extraction**
    - **Model Training**
    - **Evaluation**
    - **Save Model**

## Model yang Digunakan

- **Multinomial Naive Bayes**
- **Random Forest Classifier**
- **Logistic Regression**
- **Decision Tree Classifier**

## Evaluasi

- **Metode Evaluasi:** Akurasi, Confusion Matrix.
- **Visualisasi:** Word Cloud dan grafik performa model.

## Hasil

Hasil utama dari notebook ini adalah model machine learning siap pakai untuk klasifikasi sentimen ulasan aplikasi. Model dengan akurasi terbaik dapat di-export dan digunakan untuk prediksi data baru.

## Lisensi

Proyek ini hanya untuk keperluan pembelajaran dan riset.

---

> _README ini dihasilkan otomatis berdasarkan struktur dan kode yang ada pada notebook Pelatihan_model.ipynb. Silakan lengkapi jika ada kebutuhan atau catatan tambahan._
