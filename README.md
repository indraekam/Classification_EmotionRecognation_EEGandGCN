# 🧠 Emotion Recognition using EEG and Graph Convolutional Network

![Banner](assets/banner.png)

This project builds a machine learning pipeline to classify human emotions from **EEG signals** using a **Graph Convolutional Network (GCN)**. The model identifies emotional states (Positive, Neutral, Negative) based on frequency-domain features extracted through frame-based FFT.

---

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Platform-Google_Colab-orange?style=flat&logo=googlecolab)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-blue?style=flat&logo=tensorflow)
![GCN](https://img.shields.io/badge/Model-Graph_Convolutional_Network-purple?style=flat)
![EEG](https://img.shields.io/badge/Data-EEG_Signals-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat)

---

## 🎯 Project Goals

- Process raw EEG signals into time-frequency features using FFT
- Classify emotional states (Negative, Neutral, Positive)
- Utilize GCN for spatial-temporal pattern learning across EEG channels

---

## 📁 Project Highlights

- **EEG Dataset** structured in emotion-based folders
- Frame-based FFT with windowing for signal segmentation
- Model: TensorFlow GCN with `Softmax` output layer

---

## 🚀 How to Run (on Colab)

1. Mount Google Drive and locate EEG data directory
2. Run preprocessing cell to load and frame signals
3. Extract FFT-based features
4. Train the GCN model
5. Evaluate and visualize predictions

---

## 📂 Folder Structure

```
emotion-eeg-gcn/
├── V4_GCN_EEG_FFT.ipynb
├── assets/
│   └── banner.png
├── data/
│   ├── Positif/
│   ├── Netral/
│   └── Negatif/
```

---

## 👨‍💻 Author

**Indra Eka Mandriana S.Kom**  
_Machine Learning for Signal Processing & Cognitive Analysis_

---

## ⭐ Found this helpful? Give it a star!
