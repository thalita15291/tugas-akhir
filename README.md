# tugas akhir - sistem rekomendasi e-commerce menggunakan model hybrid

## deskripsi
repository ini dibuat untuk mendokumentasikan proses pengerjaan tugas akhir yang saya kerjakan. penelitian ini membangun sistem rekomendasi produk e-commerce dengan menggunakan metode hybrid, yaitu menggabungkan Collaborative Filtering (CF) dan Content-Based Filtering (CBF), supaya hasil rekomendasinya bisa lebih akurat.

## dataset
dataset yang digunakan dalam penelitian ini diambil dari kaggle:  
[Online Retail Dataset - Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

## metode penelitian
metode yang digunakan mengikuti tahapan CRISP-DM, mulai dari pemahaman data, pembersihan data, pembuatan model, sampai evaluasi. 
beberapa model yang digunakan di antaranya:
- **Collaborative Filtering (CF)** dengan algoritma SVD
- **Content-Based Filtering (CBF)** menggunakan TF-IDF dan cosine similarity
- **model hybrid** yang menggabungkan hasil CF dan CBF

## struktur repository
- `data/` : dataset yang digunakan
- `notebook/` : file kode Python dalam format notebook
- `laporan/` : file laporan tugas akhir (word)
- `README.md` : penjelasan repository
- `requirements.txt` : library Python yang digunakan

## hasil evaluasi
| model | RMSE | precision@5 | recall@5 |
|-------|------|-------------|----------|
| CF (SVD) | 80975.08 | - | - |
| CBF | - | 0.00 | 0.00 |
| hybrid (α=0.5) | - | 1.00 | 0.3188 |

## library yang Digunakan
- python 3 (google colab)
- pandas
- numpy
- scikit-learn
- surprise
- matplotlib

## penulis
Thalita Nadia Azalai (A11.2023.15291)  
program studi Tetknik Informatika, Universitas Dian Nuswantoro
