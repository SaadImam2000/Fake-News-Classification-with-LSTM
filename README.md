# 📰 Fake News Classification with LSTM

A binary text classification model using LSTM to detect fake vs real news articles from the WELFake dataset.

## 📌 Dataset
- **Name**: WELFake_Dataset.csv
- **Source**: [Kaggle](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)

## 🧠 Model Architecture
- Text preprocessing (title + text)
- Tokenization & padding
- LSTM (128 units) with Dropout
- Output layer: Sigmoid for binary classification

## ⚙️ Libraries
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 🚀 Results
- Test Accuracy: ~**xx%**
- F1 Score: ~**yy**

Confusion Matrix:

![Confusion Matrix](images/confusion_matrix.png)

## 🛠️ How to Run
```bash
pip install -r requirements.txt
python train_lstm.py
