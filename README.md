# Sentiment Analysis – Naive Bayes vs LSTM

In this project, I worked on classifying tweets as positive or negative using two different approaches:  
- A basic Naive Bayes model with TF-IDF  
- A deep learning model using LSTM and word embeddings

The dataset I used is [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140), which has 1.6M labeled tweets – perfect for training both traditional and deep models.

---

## 🚀 What I Did

- Cleaned and preprocessed raw tweets (removed mentions, symbols, lowercased, etc.)
- Trained a Naive Bayes classifier for a baseline (~77% accuracy)
- Then trained an LSTM-based neural network (~82% accuracy)
- Used early stopping to avoid overfitting on validation set

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy, Matplotlib  
- Scikit-learn (TF-IDF + Naive Bayes)  
- TensorFlow / Keras (Embedding, LSTM layers)

---

## 💡 Takeaways

- Deep learning clearly performs better here, but it's heavier to train  
- Preprocessing social media data is messy but super important  
- LSTM models benefit a lot from early stopping and padding sequences properly

---

## 🧪 Accuracy

- Naive Bayes: `~77%`  
- LSTM Model: `~82%`

---
