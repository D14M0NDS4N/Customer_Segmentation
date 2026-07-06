# Customer Segmentation (Superstore)

Ini bertujuan untuk mengelompokkan pelanggan (*customer segmentation*) menggunakan algoritma **K-Means Clustering**. Pendekatan yang digunakan adalah pengembangan dari metode tradisional RFM dengan menambahkan metrik diskon menjadi **RFM-D (Recency, Frequency, Monetary, Discount)** untuk memahami karakteristik perilaku belanja pelanggan secara lebih mendalam.

## 📌 Struktur File
* `Data/Superstore.csv`: Dataset transaksi ritel asli yang digunakan untuk analisis.
* `customer_segmentation.ipynb`: Jupyter Notebook yang berisi tahapan *Data Preprocessing*, *Feature Engineering* (RFM-D), *Data Scaling*, evaluasi jumlah klaster (Elbow Method & Silhouette Score), hingga *Profiling* hasil klaster.
* `Pipfile` & `Pipfile.lock`: Manajemen *environment* dan dependensi library menggunakan Pipenv.
* `*.joblib`: File model K-Means serta *scaler/transformer* yang telah dilatih dan siap digunakan untuk kebutuhan *deployment* (diabaikan dari Git via `.gitignore`).

## 🛠️ Tech Stack & Library
* **Language:** Python
* **Environment:** Jupyter Notebook, Pipenv
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 🚀 Cara Menjalankan
1. Clone repositori ini ke komputer lokal kamu.
2. Pastikan **Pipenv** sudah terinstal, lalu pasang dependensi dengan perintah:
   ```bash
   pipenv install
