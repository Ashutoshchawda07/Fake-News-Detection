📰 Fake News Detection using Machine Learning
📌 Introduction

Fake news has become a major issue in today’s digital world. In this project, we built a machine learning model to classify news articles as Real or Fake using text processing techniques and ML algorithms.

This project demonstrates:

Data preprocessing & visualization

Feature extraction using TF-IDF

Training models (Logistic Regression & Decision Tree)

Evaluating model performance

Saving models for future predictions

(Optional) Deployment with Flask/Streamlit

📊 Dataset

We used a dataset containing labeled news articles:

Label: real or fake

Text: News article content

Dataset was preprocessed to clean and vectorize the text for ML.

⚙️ Steps in Project

Data Preprocessing

Removed null values, cleaned text.

Converted labels to binary (1 = Real, 0 = Fake).

Exploratory Data Analysis (EDA)

Word clouds for most frequent words.

Bar charts of word frequencies.

Feature Extraction

Used TF-IDF Vectorizer to convert text to numerical features.

Model Training

Logistic Regression

Decision Tree Classifier

Evaluation

Accuracy Score

Confusion Matrix

Model Saving

Saved both trained models (.pkl files).

Saved TF-IDF Vectorizer for re-use during prediction.
## 📈 Results

- **Logistic Regression Accuracy**:  
  - Train: 99.35%  
  - Test: 98.97%  

- **Decision Tree Accuracy**:  
  - Train: 100%  
  - Test: 99.58%  
