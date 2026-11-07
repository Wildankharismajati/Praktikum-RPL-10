Praktikum RPL 10 – MLOps Dasar dengan Streamlit

Deskripsi Proyek

Proyek ini dibuat untuk memenuhi tugas Praktikum Rekayasa Perangkat Lunak (RPL) Pertemuan 10. Proyek ini membangun sistem prediksi kelulusan mahasiswa menggunakan Machine Learning dan Streamlit.

Aplikasi memprediksi status kelulusan mahasiswa berdasarkan dua input, yaitu IPK dan Total SKS.

Tujuan

Melatih model Machine Learning menggunakan algoritma Decision Tree.

Menyimpan model yang telah dilatih ke dalam file .pkl.

Membuat aplikasi web interaktif menggunakan Streamlit.

Menghubungkan aplikasi dengan model Machine Learning untuk melakukan prediksi.

Teknologi yang Digunakan

Python

Scikit-learn

Pandas

NumPy

Joblib

Streamlit

Struktur File

Praktik_MLOps_Streamlit/
├── 1_latih_model.py
├── app.py
├── model_kelulusan.pkl
└── requirements.txt

Cara Menjalankan Proyek

1. Instal Library

python -m pip install -r requirements.txt

2. Melatih Model

python 1_latih_model.py

Setelah dijalankan, model akan disimpan dalam file model_kelulusan.pkl.

3. Menjalankan Aplikasi

python -m streamlit run app.py

Aplikasi akan terbuka melalui browser.

Cara Menggunakan Aplikasi

Masukkan nilai IPK mahasiswa.

Masukkan jumlah Total SKS.

Klik tombol Prediksi Kelulusan.

Aplikasi akan menampilkan hasil prediksi kelulusan mahasiswa.

Algoritma

Algoritma yang digunakan adalah Decision Tree Classifier dengan data latihan sederhana yang terdiri dari IPK, Total SKS, dan label kelulusan.

Hasil

Aplikasi menghasilkan dua kemungkinan prediksi:

LULUS TEPAT WAKTU

TIDAK LULUS

Penutup

Proyek ini merupakan implementasi sederhana Machine Learning dalam aplikasi berbasis web sebagai bagian dari praktikum Rekayasa Perangkat Lunak (RPL) Pertemuan 10.
