# Fake News Classifier using LSTM

This project implements a Long Short-Term Memory (LSTM) model to classify news articles as either real or fake. Using Natural Language Processing (NLP) and deep learning techniques, the model achieves high accuracy on the Kaggle Fake News dataset.

## Project Overview
This classifier aims to help identify misinformation by analyzing the text of news articles. The model preprocesses text data and applies an LSTM-based neural network to detect patterns associated with fake news.

## Dataset
- **Source:** [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data)
- **Description:** The dataset contains news articles with labels indicating whether they are real or fake.

## Key Steps

### 1. Data Preprocessing
   - Text cleaning (removing punctuation, stop words, and performing tokenization)
   - Word embedding for representing words in vector format

### 2. Model Building
   - **Embedding Layer:** Converts text input into dense vector representations
   - **LSTM Layers:** Captures sequential dependencies in the text
   - **Dense Layers:** For binary classification

### 3. Model Evaluation
   - **Metrics Used:** Accuracy, Precision, Recall, F1-score
   - Achieved ~90% accuracy with strong F1-score across both classes


## Results

| Metric       | Value |
|--------------|-------|
| Accuracy     | 90%   |
| Precision    | 0.89  |
| Recall       | 0.91  |
| F1 Score     | 0.90  |
