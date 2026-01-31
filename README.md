# Bullying Detection using Machine Learning and Deep Learning Models

This project focuses on detecting bullying comments using multiple machine learning and deep learning models and comparing their performance.

## Overview
The goal is to classify text comments into:
- Bullying
- Non-bullying

## Dataset
- Text data loaded from an Excel file.
- Preprocessing includes:
  - Emoji to text conversion
  - Label encoding

## Models Implemented
- Logistic Regression (TF-IDF)
- Support Vector Machine (TF-IDF)
- Random Forest (TF-IDF)
- LSTM (PyTorch)
- DistilBERT (Hugging Face Transformers)

## Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Results
DistilBERT achieved the best performance:
- Accuracy: 93.09%
- F1-score: 92.89%

## Tech Stack
Python, Pandas, Scikit-learn, PyTorch, Hugging Face Transformers, Matplotlib, TF-IDF

## Future Work
- Try larger transformer models (BERT, RoBERTa)
- Deploy as a web application using Streamlit
# Bullying-Detection-NLP
Bullying detection of Youtube comments using machine learning and deep learning models
