# 📰 Advanced Fake News Detection using Deep Learning and NLP

This project is designed to accurately detect **fake news articles** using advanced Natural Language Processing (NLP) techniques and Deep Learning. The system analyzes the content of news articles and classifies them as *Real* or *Fake*, aiming to curb misinformation on digital platforms.

---

## 📂 Project Structure


---

## ✅ Features

- Text classification using Deep Learning (LSTM)
- Advanced NLP pipeline: Lemmatization, Bag of Words, Named Entity Recognition (NER), Sentiment Analysis
- Data visualization with Word Clouds and Heatmaps
- Binary classification: Detects whether a news article is *Fake* or *Real*
- Trained on a real-world dataset

---

## 🧠 NLP & Deep Learning Techniques Used

- **Text Preprocessing**: Removal of punctuation, lowercasing, stopword filtering, lemmatization
- **Bag of Words (BoW)** representation
- **Named Entity Recognition (NER)**
- **Sentiment Analysis**
- **LSTM (Long Short-Term Memory)** network for sequential deep learning
- **Binary Classification**: Output is either “Fake” or “Real” (no probability score shown)

---

## 📊 Dataset

- File: `news.csv`
- Contains two main fields: `text` and `label`
  - `text`: Full news article or headline
  - `label`: 0 = Fake, 1 = Real

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Advanced-Fake-News-Detection.git
cd Advanced-Fake-News-Detection
