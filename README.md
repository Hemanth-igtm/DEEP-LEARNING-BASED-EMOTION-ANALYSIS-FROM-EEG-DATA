# DEEP-LEARNING-BASED-EMOTION-ANALYSIS-FROM-EEG-DATA

This project implements an **emotion recognition system using EEG (Electroencephalography) data** with a **Long Short-Term Memory (LSTM) neural network**. The model classifies emotional states based on EEG signals, leveraging deep learning for accurate predictions.

---

## 📌 Features
- Preprocessing of EEG data:
  - Label Encoding
  - One-Hot Encoding
  - Feature Scaling
- Reshaping data for LSTM input
- Deep Learning Model:
  - Two LSTM layers with Dropout
  - Dense layers for classification
- Early stopping for optimal training
- Model saved as `eeg_LSTM_emotion_model.h5`

---

## 📂 Project Structure
project/
│
├── emotions.csv # EEG dataset
├── EEG_Emotion_LSTM.ipynb # Jupyter Notebook (main code)
├── eeg_LSTM_emotion_model.h5 # Trained model (optional)
└── README.md # Project documentation

## ⚙️ Requirements
Install the following dependencies:
```bash
pip install pandas numpy scikit-learn tensorflow keras
