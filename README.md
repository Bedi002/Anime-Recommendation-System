# Sistem Rekomendasi Anime Menggunakan K-Means Clustering

Proyek ini adalah Final Project untuk mata kuliah Big Data & Data Mining. Sistem ini bertujuan untuk memberikan rekomendasi anime berdasarkan kemiripan genre, rating, dan popularitas menggunakan algoritma Machine Learning.

##  Dataset
Dataset yang digunakan berasal dari Kaggle: Anime Recommendations Database.
Fokus pemrosesan menggunakan file `anime.csv` yang berisi informasi detail tentang judul, genre, rating, dan jumlah member.

##  Metode yang Digunakan
* **Preprocessing:** Data Cleaning, One-Hot Encoding (Genre), StandardScaler.
* **Algorithm:** K-Means Clustering.
* **Evaluation:** Elbow Method & Silhouette Score.

##  Cara Menjalankan Project
1. Clone repository ini.
2. Pastikan library berikut sudah terinstall:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
3. Buka file `Final_Project_Sistem_Rekomendasi_Anime.ipynb` menggunakan Jupyter Notebook atau Google Colab.
4. Jalankan setiap sel (cell) secara berurutan.

##  Hasil Evaluasi
Model optimal terbentuk pada **10 Cluster** berdasarkan analisis Elbow Method. Sistem berhasil mengelompokkan anime populer dan anime niche ke dalam segmen yang berbeda.
