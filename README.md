# 🐾 Animals-10 Image Classification with MobileNetV2

## 📌 Overview
Sistem klasifikasi gambar untuk mengenali 10 spesies hewan berbeda (kucing, anjing, ayam, dll) menggunakan **Convolutional Neural Networks (CNN)**.

## 🧠 Architecture
Proyek ini menggunakan teknik **Transfer Learning** dengan arsitektur **MobileNetV2** yang telah dilatih pada ImageNet.
* **Base Model:** MobileNetV2 (Frozen layers).
* **Custom Head:** GlobalAveragePooling -> Dense -> Dropout -> Output (Softmax).
* **Optimization:** Adam Optimizer, Learning Rate 0.0001.

## 📈 Results
* **Training Accuracy:** 96%
* **Validation Accuracy:** 95.85%
* **Loss:** 0.13 (Converged)

## 📱 Deployment
Model dikonversi ke format:
* `.h5` (Keras/TensorFlow)
* `.tflite` (Mobile Deployment)
* `.json` (TensorFlow.js for Web)

Link Google Drive: https://drive.google.com/drive/folders/1-6_YKGB433oncHB_xm_edHGLGNF3oQ8v?usp=sharing

## 🔧 Requirements
`tensorflow`, `numpy`, `matplotlib`, `pillow`
