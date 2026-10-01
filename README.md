# Sentiment-Analysis
Develop machine learning models to classify emotions in text samples.

This project uses Natural Language Processing (NLP) and machine learning to classify text comments into different emotion categories such as anger, fear, joy, and sadness.

Workflow

1. Data Preprocessing – Cleaned the comments by converting text to lowercase, removing unnecessary characters, tokenizing the text, and removing stop words.


2. Feature Extraction – Used TF-IDF Vectorizer to convert text into numerical features based on word importance.


3. Model Development – Trained two machine-learning models:

Naive Bayes: A simple and efficient model that works well with text and TF-IDF features.

Support Vector Machine (SVM): Effective for high-dimensional text features and separating different emotion classes.

4. Model Evaluation – Compared the models using Accuracy and Weighted F1-score.
