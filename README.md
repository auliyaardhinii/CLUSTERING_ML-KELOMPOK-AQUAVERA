# Clustering Data Sales Retail - Tugas Besar Machine Learning

Proyek ini merupakan tugas besar mata kuliah Pembelajaran Mesin yang bertujuan untuk mengelompokkan data penjualan retail menggunakan algoritma K-Means. Pemodelan dilakukan tanpa library machine learning (from scratch), dilengkapi dengan evaluasi menggunakan metode Silhouette Score dan WCSS (Within-Cluster Sum of Squares) untuk menentukan jumlah klaster terbaik.

Analisis ini membantu dalam mengidentifikasi pola penjualan dan segmentasi data berdasarkan karakteristik yang serupa. Visualisasi hasil klaster ditampilkan dalam bentuk 2D menggunakan PCA.

Disusun oleh kelompok Aquavera, Telkom University :
1. AULIYA ARDHINI PUTRI / 1206230020 DS-03-02
2. NUR NISRINA SALSABILLA / 1206230020 DS-03-02
3. AYUNDA DEWI AGUSTIN / 1206230020 DS-03-02
   
## 📌 Tujuan
- Mengelompokkan data berdasarkan pola pembelian/penjualan.
- Mengidentifikasi jumlah klaster terbaik dengan metode evaluasi seperti:
  - **Silhouette Score**
  - **WCSS (Within-Cluster Sum of Squares)**

## 🧪 Metode
- Implementasi manual algoritma K-Means tanpa library scikit-learn.
- Evaluasi dilakukan untuk k = 2 hingga k = 7.
- Visualisasi hasil clustering dengan PCA 2D.

## 📝 Struktur Folder
- `CLUSTERING_ML_FINAL.ipynb`: Notebook utama berisi seluruh proses.
- `results/`: Gambar hasil clustering dan evaluasi.
- `laporan/`: File laporan akhir.
- `data/`: Dataset mentah dan bersih
