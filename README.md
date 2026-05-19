# Repository Submission Dicoding — Eka Adit Prasetyo

Repositori ini berisi kumpulan proyek submission dari beberapa kelas Dicoding yang dikerjakan sebagai bagian dari proses belajar. Setiap folder di dalam repositori ini merepresentasikan masing-masing kelas dan submission terkait.

## Daftar Proyek

### 1. Belajar Machine Learning untuk Pemula

Proyek ini berfokus pada analisis dataset *Fraud Detection* dan identifikasi anomali transaksi dengan pendekatan *hybrid machine learning*.

**Gambaran umum:**

* Tahap pertama menggunakan *unsupervised learning* dengan *K-Means Clustering* untuk menemukan pola alami data nasabah.
* Hasil clustering kemudian dijadikan label target untuk tahap kedua menggunakan *supervised learning*.
* Model klasifikasi dibangun dengan *Decision Tree Classifier* untuk memprediksi kategori nasabah baru.

**Hasil utama:**

* Data berhasil dibersihkan dan diproses menjadi dataset yang siap untuk *modeling*.
* Terbentuk 2 cluster utama dengan karakteristik perilaku transaksi yang berbeda.
* Model klasifikasi berhasil dilatih, dievaluasi, dan diekspor untuk kebutuhan penggunaan lanjutan.

### 2. Belajar Fundamental Deep Learning (Proyek Pertama) — Analisis Sentimen Ulasan Shopee

Proyek ini bertujuan untuk mengklasifikasikan sentimen ulasan pengguna Shopee ke dalam tiga kelas: positif, netral, dan negatif.

**Gambaran umum:**

* Data dikumpulkan melalui *web scraping* menggunakan *google-play-scraper*.
* Pelabelan dilakukan secara semi-otomatis dengan pendekatan *lexicon-based* dan aturan buffer zone.
* Model dibangun menggunakan beberapa arsitektur *Recurrent Neural Network*, yaitu LSTM, BiLSTM, dan GRU.

**Hasil utama:**

* Dataset berhasil diproses dan dilabeli secara konsisten.
* Tiga skema pelatihan berhasil melampaui target akurasi.
* Model terbaik adalah BiLSTM dengan akurasi validasi 87.85%.

### 3. Belajar Fundamental Deep Learning (Proyek Akhir) — Vegetable Image Classification

Proyek ini membangun model *image classification* untuk mengenali 15 jenis sayuran dari dataset berisi lebih dari 20.000 gambar.

**Gambaran umum:**

* Dataset diambil dari Kaggle dan dibagi secara mandiri menjadi *train*, *validation*, dan *test*.
* Pra-pemrosesan dilakukan dengan normalisasi dan augmentasi gambar.
* Model dikembangkan menggunakan *Convolutional Neural Network* dengan TensorFlow/Keras.

**Hasil utama:**

* Model mampu belajar pola visual dari gambar sayuran secara efektif.
* Performa pelatihan dan validasi mencapai akurasi tinggi.
* Model berhasil diekspor ke beberapa format deployment: SavedModel, TFLite, dan TFJS.

### 4. Membangun Sistem Machine Learning — Water Potability

Proyek ini berfokus pada pengembangan sistem *machine learning* end-to-end untuk memprediksi kelayakan air minum.

**Gambaran umum:**

* Workflow otomatis dibangun dengan GitHub Actions dan MLflow Project.
* Eksperimen model dilacak menggunakan MLflow dan DagsHub.
* Model disajikan melalui REST API dengan MLflow Models Serve.
* Monitoring sistem dilakukan dengan Prometheus dan Grafana.
* Notifikasi anomali dikirim ke Telegram melalui konfigurasi alerting.

**Hasil utama:**

* Pipeline berjalan otomatis dari preprocessing hingga training.
* Model berhasil di-*serve* untuk inferensi real-time.
* Sistem monitoring dan alerting berjalan dengan baik dan dapat mendeteksi anomali performa.

## Struktur Repositori

Setiap folder di repositori ini disusun berdasarkan kelas atau submission yang dikerjakan. Secara umum, isi setiap folder dapat mencakup:

* kode sumber proyek
* dataset hasil olahan atau referensi pemrosesan
* notebook eksplorasi dan pelatihan model
* model yang sudah diekspor
* visualisasi hasil evaluasi
* dokumentasi pendukung

## Teknologi yang Digunakan

* Python
* TensorFlow / Keras
* scikit-learn
* pandas
* NumPy
* matplotlib / seaborn
* MLflow
* GitHub Actions
* Prometheus
* Grafana
* Telegram Bot API

## Cara Menjalankan Proyek

Karena setiap submission memiliki kebutuhan yang berbeda, langkah menjalankan proyek dapat bervariasi antar folder. Secara umum:

1. Clone repositori ini.
2. Masuk ke folder submission yang ingin dijalankan.
3. Buat virtual environment jika diperlukan.
4. Install seluruh dependensi yang tercantum pada file `requirements.txt` atau notebook terkait.
5. Jalankan notebook, script training, atau API sesuai petunjuk pada masing-masing folder.

## Catatan

* Setiap folder di dalam repositori ini merepresentasikan masing-masing kelas dan submission terkait.
* Kode-kode pada repositori ini telah diverifikasi dan memenuhi kriteria kelulusan dari tim reviewer Dicoding.
* Mohon tidak melakukan plagiarisme, gunakan repositori ini sebagai referensi untuk belajar.

## Lisensi

Repositori ini dibuat untuk tujuan pembelajaran dan dokumentasi hasil submission. Silakan gunakan secara bijak dan tetap hormati etika akademik.
