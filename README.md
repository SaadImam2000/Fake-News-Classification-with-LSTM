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
- Test Accuracy: 97.36%
- F1 Score: 97

Confusion Matrix:


![confusionMatrix](https://github.com/user-attachments/assets/9796312e-f020-4229-a3fc-7ba6ea97f7cc)


## 🛠️ How to Run
```bash
python train_lstm.py
