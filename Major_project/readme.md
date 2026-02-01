📰 Fake News Classification using Machine Learning

A complete end-to-end Machine Learning project that classifies news articles as FAKE or REAL using Natural Language Processing (NLP) and Logistic Regression.

📌 Project Overview

With the rapid spread of misinformation on the internet, detecting fake news has become a critical challenge.
This project builds a machine learning model that automatically analyzes news text and predicts whether it is Fake News or Real News.

The system is trained on labeled datasets and uses NLP techniques to convert raw text into numerical features before classification.

🚀 Features

Loads and processes large fake and real news datasets

Cleans and merges text data

Converts text into numerical features using TF-IDF Vectorization

Trains a Logistic Regression model

Evaluates performance using accuracy score

Supports prediction on custom user input.
🛠 Technologies Used

1.Python

2.Pandas

3.Scikit-learn

4.NLP (Natural Language Processing)

5.TF-IDF Vectorizer

Logistic Regression

Jupyter Notebook

📂 Dataset Information

The project uses two CSV datasets:

Fake.csv – contains fake news articles

True.csv – contains real news articles

Each dataset includes:

Title
Text
Subject
Date

A new column called label is added:

0 → Fake News

1 → Real News

Both datasets are merged and shuffled before training.

🧪 Machine Learning Workflow

Load Datasets

Add Labels (Fake = 0, Real = 1)

Combine and Shuffle Data

Text Preprocessing

Convert Text to Numerical Form using TF-IDF

Train-Test Split

Train Logistic Regression Model

Evaluate Accuracy

Predict on Custom Input.

🧠 Model Used
Logistic Regression

Simple and effective for text classification

Works well with high-dimensional sparse data

Fast to train and easy to interpret.

📦 Future Improvements

Add deep learning models like LSTM or BERT

Build a Flask or Streamlit web interface

Deploy as a real-time API

Improve text preprocessing

Add more datasets for better generalization
