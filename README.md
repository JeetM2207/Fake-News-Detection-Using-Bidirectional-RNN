# 📰 Fake News Detection using Bidirectional RNN

This project aims to classify news articles as **Fake** or **Real** using deep learning. It uses a **Bidirectional Recurrent Neural Network (BiRNN)** to capture contextual word representations in both directions, making it well-suited for text classification tasks.

---

## ✅ Project Highlights

- Uses a Bidirectional RNN (with LSTM or GRU cells) for binary classification.
- Trained on a labeled fake news dataset.
- Includes preprocessing, tokenization, model training, and evaluation.
- Potential real-world application in identifying misinformation.

---


---

## 📦 Dataset

- **Source**: Kaggle Fake News Dataset or similar
- **Features**:
  - `title`: Headline of the news article
  - `text`: Full news content
  - `label`: 0 = Real, 1 = Fake

---

## 🧠 Model Architecture

- **Embedding Layer** (Word embeddings from Keras tokenizer)
- **Bidirectional LSTM / GRU**
- **Dropout Layer** (to prevent overfitting)
- **Dense Layer with Sigmoid Activation** (for binary classification)

---

## 🔍 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix

---




