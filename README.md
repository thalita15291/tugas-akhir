# Tugas Akhir - Sistem Rekomendasi E-Commerce Menggunakan Model Hybrid

## Deskripsi
Repository ini dibuat untuk mendokumentasikan proses pengerjaan tugas akhir yang saya kerjakan. Penelitian ini membangun sistem rekomendasi produk e-commerce dengan menggunakan metode hybrid, yaitu menggabungkan Collaborative Filtering (CF) dan Content-Based Filtering (CBF), supaya hasil rekomendasinya bisa lebih akurat.

## Dataset
Dataset yang digunakan dalam penelitian ini diambil dari Kaggle:  
[Online Retail Dataset - Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

## Metode Penelitian
Metode yang digunakan mengikuti tahapan CRISP-DM, mulai dari pemahaman data, pembersihan data, pembuatan model, sampai evaluasi. 
Beberapa model yang digunakan di antaranya:
- **Collaborative Filtering (CF)** dengan algoritma SVD
- **Content-Based Filtering (CBF)** menggunakan TF-IDF dan cosine similarity
- **Model Hybrid** yang menggabungkan hasil CF dan CBF

## Struktur Repository
- `data/` : Dataset yang digunakan
- `notebook/` : File kode Python dalam format notebook
- `laporan/` : File laporan tugas akhir (Word)
- `README.md` : Penjelasan repository
- `requirements.txt` : Library Python yang digunakan

## Hasil Evaluasi
| Model | RMSE | Precision@5 | Recall@5 |
|-------|------|-------------|----------|
| CF (SVD) | 80975.08 | - | - |
| CBF | - | 0.00 | 0.00 |
| Hybrid (α=0.5) | - | 1.00 | 0.3188 |

## Library yang Digunakan
- Python 3 (Google Colab)
- pandas
- numpy
- scikit-learn
- surprise
- matplotlib

## Penulis
Thalita Nadia Azalai (A11.2023.15291)  
Program Studi Teknik Informatika, Universitas Dian Nuswantoro
