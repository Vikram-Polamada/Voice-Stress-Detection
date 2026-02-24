# 🎤 Voice Stress Detection using Machine Learning

A machine learning project that detects stress in human speech using MFCC, spectral features, and pitch-based time-series analysis.

---

## 🚀 Project Overview

This project:

- 🔊 Uses the RAVDESS emotional speech dataset
- 🎧 Extracts MFCC, Delta, ZCR, Spectral & Pitch features
- 🧠 Trains classical ML models (SVM & Random Forest)
- 🧪 Performs random split, cross-validation & speaker-independent tests
- 📈 Achieves up to **97% accuracy**

The goal is to build a system that automatically identifies vocal stress patterns from audio recordings.

---

## 📂 Dataset Information

The dataset contains:

- 24 actors (12 male, 12 female)
- 1440 WAV files (studio-quality)
- 8 emotion categories

### 🎯 Binary Label Mapping

- `0` → Normal Speech (Neutral, Calm)
- `1` → Stressed Speech (Angry, Fearful)

---

## 🎛 Features Extracted

The project extracts multiple time-series & spectral features:

- 🎚 **MFCC (13 Coefficients)**
- 🔁 **Delta & Delta-Delta MFCC**
- 📉 **Zero Crossing Rate (ZCR)**
- 🌐 **Spectral Centroid**
- 🔊 **RMS Energy**
- 🎵 **Pitch Mean & Pitch Variation**

These features capture stress-related variations like increased pitch, higher energy, and spectral shifts.

---

## 🏗 Model Workflow

1️⃣ Audio Loading  
2️⃣ Preprocessing (Resampling, STFT)  
3️⃣ Feature Extraction  
4️⃣ Feature Scaling (StandardScaler)  
5️⃣ Train-Test Split  
6️⃣ Model Training (SVM, Random Forest)  
7️⃣ Cross-Validation  
8️⃣ Evaluation & Prediction  
