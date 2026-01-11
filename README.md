# Speech Signal Emotion Detection

This repository contains a **Speech Emotion Recognition (SER)** system that detects human emotions from speech signals using audio feature extraction and machine learning / deep learning techniques.

The project processes raw speech signals, extracts meaningful acoustic features, and classifies emotions such as **happy, sad, angry, neutral**, etc.

---

## 🚀 Project Overview

- **Input:** Speech audio signals (.wav files)
- **Output:** Predicted emotion labels
- **Approach:**
  1. Audio preprocessing
  2. Feature extraction (MFCC, Chroma, Mel, etc.)
  3. Model training and evaluation
  4. Emotion prediction

This notebook provides a complete pipeline from raw audio to emotion classification.

---

## ✨ Key Features

- **Audio Preprocessing**
  - Noise handling
  - Signal normalization
  - Sampling rate consistency

- **Feature Extraction**
  - MFCC (Mel Frequency Cepstral Coefficients)
  - Chroma features
  - Mel Spectrogram
  - Spectral features

- **Emotion Classification**
  - Supervised learning for emotion prediction
  - Performance evaluation using accuracy and confusion matrix

- **Visualization**
  - Waveform plots
  - Spectrograms
  - Training curves and evaluation metrics

---

## 🛠 Tech Stack

### Audio Processing
- Librosa
- NumPy
- SciPy

### Machine Learning / Deep Learning
- Scikit-learn
- TensorFlow / Keras *(if used in notebook)*

### Visualization
- Matplotlib
- Seaborn

---

## 📂 File Structure

```text
.
├── Speech_signal_emotion_detection_final.ipynb
├── female_features
└── README.md
