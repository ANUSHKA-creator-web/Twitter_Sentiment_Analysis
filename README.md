Twitter Sentiment Analysis
Project Overview

This project implements a deep learning-based sentiment analysis system for Twitter data, classifying tweets as positive or negative. It leverages LSTM neural networks to capture sequential dependencies in text and predict sentiment. The dataset contains 30,000 labeled tweets, and the workflow includes data preprocessing, model training, evaluation, and inference.

Features

Data Handling & EDA: Loads and explores tweet text and sentiment labels.

Text Preprocessing Pipeline:

Removal of special characters, URLs, and noise

Lowercasing, tokenization, stopword removal, and lemmatization using NLTK

Text Vectorization: Keras Tokenizer to convert text to sequences, followed by padding for uniform input length.

Model Architecture: LSTM network with embedding, dropout, and dense layers for binary classification.

Training & Evaluation: Trains with validation, tracks accuracy and loss, and visualizes performance.

Model Persistence: Save and reload the trained model for future predictions.

Inference Demo: Predict sentiment on new tweet examples.

Installation

Clone the repository:
