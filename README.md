# Sentiment Classification Using Embeddings

An embedding-based sentiment classification system that classifies tweets into **Positive, Negative, or Neutral** using semantic embeddings and machine learning models.

---

## 📖 Project Overview

Social media platforms generate millions of posts daily. Understanding public sentiment is crucial for:

- Brand monitoring  
- Crisis management  
- Public opinion analysis  
- Data-driven decision making  

This project uses **sentence embeddings** to capture semantic meaning of tweets and trains machine learning models to classify sentiment effectively.

---

## 🚀 Features

✔ Text preprocessing and cleaning  
✔ Exploratory Data Analysis (EDA)  
✔ WordCloud visualization  
✔ Embedding generation using SentenceTransformers  
✔ Logistic Regression model  
✔ XGBoost model  
✔ Model evaluation (Accuracy, Precision, Recall, F1-score)  
✔ Confusion Matrix visualization  
✔ Custom sentiment predictions  

---

## 🗂 Dataset

**Twitter Tweets Sentiment Dataset**  
- Size: ~27,000 tweets  
- Labels: Positive, Negative, Neutral  
- Columns: `text`, `sentiment`  

Dataset Source:  
https://www.kaggle.com/datasets/yasserh/twitter-tweets-sentiment-dataset

---

## 🧠 Methodology

### 1️⃣ Text Preprocessing
- Lowercasing
- URL removal
- Mention removal
- Special character cleaning
- Whitespace normalization

### 2️⃣ Embedding Generation
We use:

from SentenceTransformers to convert text into dense vector representations.

### 3️⃣ Model Training
Two models were trained:

- Logistic Regression
- XGBoost Classifier

### 4️⃣ Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~80–85% |
| XGBoost | ~85–90% |

XGBoost performed better due to its ability to capture complex decision boundaries.

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/sentiment-classification-embeddings.git
cd sentiment-classification-embeddings

pip install -r requirements.txt
pip install sentence-transformers xgboost seaborn wordcloud kagglehub


▶ How to Run

Open the notebook in Google Colab

Run all cells

View EDA visualizations and model results

🔮 Example Predictions
Tweet	Prediction
"I love this product!"	Positive
"Worst experience ever."	Negative
"It was okay, nothing special."	Neutral
📌 Key Insights

Embeddings significantly improve sentiment understanding compared to traditional Bag-of-Words.

XGBoost outperforms Logistic Regression in classification accuracy.

The model can be extended for real-time social media monitoring.

📈 Future Improvements

Hyperparameter tuning

Deep learning classifiers (LSTM, Transformers)

Deployment using FastAPI or Streamlit

Real-time Twitter API integration

Multilingual sentiment analysis

👨‍💻 Author

Zamin Askari Rizvi

Aspiring AI Engineer | Full Stack Developer | NLP Enthusiast
