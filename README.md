# Judul Project
Memprediksi lama rawat inap pasien di rumah sakit dengan model machine learning

## Repository Outline
1. README.md - Deskripsi dokumentasi project
2. notebook_inference_muhammad_iqbal.ipynb - Notebook yang berisi model inference 
3. notebook_project_muhammad_iqbal.ipynb - Notebook yang berisi pengolahan data dengan python
4. LengthOfStay.csv - dataset yg digunakan dalam projek
5. model.pkl - Hasil model untuk deployments

## Problem Background
Rumah sakit merupakan salah infrastruktur penting dalam suatu negara. Dimana setiap harinya banyak pasien yg datang kerumah sakit untuk rawat inap atau konsultasi dokter. Di beberapa sumber, rumah sakit di indonesia tak jarang yg mengalami Overload karena manajemen rumah sakit yg kurang dan jumlah pasien yg tidak terprediksi pada suatu waktu, sehingga menyebabkan ketidakseimbangan dalam alokasi tempat tidur dan tenaga medis. Dataset yg dipakai pada projek kali ini berisi tentang faktor - faktor seperti riwayat medis, jenis penyakit, dan lain lain.

## Project Output
Output project adalah model machine learning dan model deployment

## Data
Dataset yang digunakan dalam proyek ini berasal dari **Kaggle.com** dan berisi:  
- **100 ribu baris data**  
- **28 fitur**, termasuk kondisi kesehatan pasien, indikator medis, dan lama rawat inap

## Method
Project ini mengenai machine learning regressi sehingga metode yang dipakai adalah model supervised learning dengan model Linear Regression, Decision Tree Regression, dan XGB Regressor.

## Stacks
- **Bahasa Pemrograman**: Python  
- **Library**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Plotly, Seaborn  
- **Deployment**: Streamlit

## Hasil & Implementasi  
- Model terbaik dipilih adalah XGB Regressor berdasarkan hasil evaluasi  
- Mendapatkan R2 score di angka 0,81 dan nilai error MAE di 0,7
- Model diterapkan dalam aplikasi berbasis **Streamlit** untuk mempermudah penggunaannya di rumah sakit

## Reference
- Dataset: [Hospital Length of Stay Dataset Microsoft](https://www.kaggle.com/datasets/aayushchou/hospital-length-of-stay-dataset-microsoft/data)  
- Panduan Machine Learning: [Scikit-learn Documentation](https://scikit-learn.org/)  
- Demo Deployment : [Predciting Hospital LOS - Huggingface](https://huggingface.co/spaces/mbale014/Predicting-Hospital-LOS)

---
