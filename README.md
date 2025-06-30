# Multi-Class Emotion Detection with Deep Learning

This project classifies emotions in tweets using LSTM, CNN, GRU, and ensemble models. It covers the full NLP pipeline—from preprocessing to model training and evaluation—achieving up to **92.5% accuracy**.

---

## 💡 Overview

- Multi-class classification: 6 emotion categories (e.g., joy, anger, sadness)
- Built and compared LSTM, CNN, and GRU models
- Ensemble model improved overall accuracy and balance
- Used real-world tweet data

---

## 📊 Model Performance

| Model   | Accuracy |
|---------|----------|
| LSTM    | 92.5%    |
| CNN     | 90.8%    |
| GRU     | 91.7%    |
| Ensemble | **93.2%** |

---

## 🔧 Tech Stack

- Python 3.x
- TensorFlow / Keras
- NLTK, Scikit-learn
- Matplotlib, Seaborn

---

## 📁 Structure

- `notebooks/`: Full workflow in Jupyter notebooks
- `src/`: Helper modules for preprocessing and training
- `models/`: Saved models (sample files)
- `results/`: Evaluation plots, confusion matrices

---

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
