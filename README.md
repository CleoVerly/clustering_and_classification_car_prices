# clustering_and_classification_car_prices
# Proyek Submission Machine Learning untuk Pemula

Repositori ini berisi dua proyek akhir sebagai bagian dari submission kelas **"Belajar Machine Learning untuk Pemula"**. Proyek ini mencakup implementasi dari dua tugas utama dalam machine learning: **Klasifikasi** dan **Clustering**.

**Oleh:** Muhammad Agusriansyah

***

## Struktur Repositori 📂

Struktur file dan folder dalam repositori ini adalah sebagai berikut:
```
clustering_and_classification_car_prices/
├── dataset/
│   ├── car_prices.csv
│   └── hasil_clustering.csv
├── [Klasifikasi]_Submission_Akhir_BMLP_Muhammad_Agusriansyah.ipynb
├── [Clustering]_Submission_Akhir_BMLP_Muhammad_Agusriansyah.ipynb
├── requirements.txt
└── README.md
```
***

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan teknologi dan pustaka berikut:

* **Python**
* **Jupyter Notebook**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

***

## Deskripsi Proyek 📝

### 1. Clustering

Proyek ini berfokus pada penerapan algoritma *unsupervised learning* untuk mengelompokkan data ke dalam beberapa segmen atau *cluster* berdasarkan kesamaan karakteristiknya.

* **Notebook**: `[Clustering]_Submission_Akhir_BMLP_Muhammad_Agusriansyah.ipynb`

**Ringkasan Proses**:
1.  **Persiapan Data**: Menggunakan dataset yang tidak memiliki label, dengan jumlah data minimal 1000 baris serta memiliki fitur numerik dan kategorik.
2.  **Pemodelan**: Mengimplementasikan algoritma clustering (misalnya K-Means) untuk menemukan pola alami dalam data. Jumlah cluster yang optimal ditentukan menggunakan metode seperti *Elbow method*.
3.  **Analisis Cluster**: Menganalisis karakteristik setiap cluster yang terbentuk. Dalam proyek ini, analisis difokuskan pada hubungan antara `Annual Income` (Pendapatan Tahunan) dan `Spending Score` (Skor Pengeluaran).
4.  **Ekspor Hasil**: Hasil akhir dari proses clustering, yaitu data yang telah diberi label cluster, diekspor dan disimpan dalam file `hasil_clustering.csv`.

### 2. Klasifikasi

Proyek ini bertujuan untuk membangun dan mengevaluasi beberapa model klasifikasi untuk memprediksi suatu target berdasarkan fitur-fitur yang ada.

* **Notebook**: `[Klasifikasi]_Submission_Akhir_BMLP_Muhammad_Agusriansyah.ipynb`

**Ringkasan Proses**:
1.  **Persiapan Data**: Melakukan pemuatan data, pembersihan, dan analisis data eksplorasi (EDA) untuk memahami distribusi dan korelasi antar fitur.
2.  **Pra-pemrosesan Data**: Menerapkan teknik seperti *Label Encoding* untuk data kategorikal dan *Standard Scaling* atau *Min-Max Scaling* untuk menormalisasi data numerikal.
3.  **Pemodelan**: Membangun dan melatih beberapa model klasifikasi:
    * K-Nearest Neighbors (KNN)
    * Decision Tree
    * Random Forest
    * Support Vector Machine (SVM)
    * Gaussian Naive Bayes
4.  **Evaluasi Model**: Kinerja setiap model dievaluasi menggunakan metrik seperti *accuracy*, *precision*, *recall*, *F1-score*, dan *confusion matrix* untuk menemukan model dengan performa terbaik.
5.  **Rekomendasi**: Berdasarkan hasil evaluasi, diberikan rekomendasi untuk perbaikan model, seperti penggunaan *cross-validation* untuk mengatasi *overfitting* atau transformasi fitur untuk menangani *underfitting*.

***

## Cara Menjalankan 🚀

Untuk menjalankan notebook dan mereplikasi hasil dari proyek ini, ikuti langkah-langkah di bawah ini:

1.  **Kloning Repositori**
    ```bash
    git clone https://github.com/CleoVerly/clustering_and_classification_car_prices.git

    ```

2.  **Instalasi Dependensi**
    Pastikan Anda memiliki Python dan Jupyter Notebook terinstal. Instal semua pustaka yang dibutuhkan menggunakan pip.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Jalankan Notebook**
    Buka dan jalankan file `.ipynb` menggunakan Jupyter Notebook atau JupyterLab.
    ```bash
    jupyter notebook
    ```
## 📄 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT**. Lihat file `LICENSE` untuk detail lebih lanjut.

