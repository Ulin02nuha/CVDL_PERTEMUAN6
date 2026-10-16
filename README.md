# Klasifikasi Citra Buah (Apple, Cherry, Tomato) Menggunakan Inception-v4

Proyek ini mengimplementasikan Convolutional Neural Network (CNN) berarsitektur **Inception-v4** berbasis *pretrained model* untuk mengklasifikasikan tiga jenis buah dari dataset Fruits-360.

## 📌 Ringkasan Hasil Eksperimen
- **Testing Accuracy Tertinggi**: 90,53% (Epoch 1)
- **Training Accuracy**: 99,80% (Epoch 3)
- **Hyperparameter**: Adam Optimizer (Learning Rate = 0,0001), Batch Size = 16, 3 Epochs

## 📊 Kinerja Per Kelas (F1-Score)
- **Apple**: 97,07%
- **Tomato**: 86,39%
- **Cherry**: 81,74%

## 📁 Struktur File
- `Untitled2.ipynb`: Notebook eksperimen lengkap PyTorch.
- `confusion_matrix.png`: Hasil visualisasi prediksi matriks konfusi.
- `grafik_kinerja.png`: Grafik perbandingan Loss dan Accuracy selama pelatihan.
