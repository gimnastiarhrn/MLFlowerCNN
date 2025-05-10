# Image Classification Project - Flower Dataset 🌸

## Deskripsi Proyek

Proyek ini bertujuan untuk mengklasifikasikan gambar bunga ke dalam 5 kategori berbeda menggunakan Convolutional Neural Network (CNN) dengan TensorFlow dan Keras. Dataset yang digunakan terdiri dari lebih dari 1000 gambar bunga yang telah diproses dan dibagi menjadi data latih dan validasi. Model yang dibangun mampu mencapai akurasi validasi lebih dari 85% dengan teknik augmentasi data untuk meningkatkan performa.

## Fitur Utama

- Preprocessing dan augmentasi data gambar secara real-time  
- Arsitektur CNN yang sederhana namun efektif  
- Pelatihan model dengan monitoring akurasi dan loss  
- Evaluasi model menggunakan grafik dan confusion matrix  
- Konversi model ke format SavedModel, TF-Lite, dan TFJS  
- Contoh kode inference untuk prediksi gambar baru  

## Persyaratan Sistem

- Python 3.7 atau lebih baru  
- TensorFlow 2.x  
- NumPy  
- Matplotlib  
- scikit-learn  

Instal semua dependensi dengan perintah:

```bash
pip install -r requirements.txt
