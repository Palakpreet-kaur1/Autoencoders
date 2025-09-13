# Arabic Handwritten Digits Autoencoder

This project implements an **autoencoder** for dimensionality reduction and reconstruction of handwritten Arabic digits. The goal is to compress the images into a lower-dimensional representation while maintaining the ability to accurately reconstruct the original input.

## 📌 Project Overview
- **Dataset:** Arabic Handwritten Digits Dataset (28x28 grayscale images)  
- **Task:** Encode digit images into a compact latent space and decode them back to reconstruct the originals.  
- **Purpose:** Reduce storage needs, preserve essential features, and explore deep learning techniques for image representation.

## ⚙️ Features
- Data preprocessing with **pandas** and **NumPy**  
- Image visualization using **Matplotlib**  
- Autoencoder built using **Keras** (TensorFlow backend)  
- Training pipeline for encoding/decoding images  
- Visualization of reconstructed images compared to originals

## 🧠 Model Architecture
- **Encoder:** Compresses 28x28 input images into a lower-dimensional latent vector  
- **Decoder:** Reconstructs images from the compressed latent representation  

## 📊 Results
- Successfully reconstructed handwritten digits while reducing dimensionality  
- Learned compact latent representations suitable for storage and further tasks (e.g., classification)  
- Visual comparisons show strong reconstruction accuracy


