# Narendra Modi Tweets Sentiment Analysis

This repository contains tools and models for analyzing and classifying sentiment in tweets related to Narendra Modi using Natural Language Processing (NLP) techniques and machine learning models.

## Overview

The project focuses on sentiment analysis of tweets to understand public opinion and sentiment dynamics related to Narendra Modi. Various machine learning models and NLP techniques are employed for this purpose, including XGBoost, Random Forest, Gradient Boosting, Support Vector Machine (SVM), LSTM neural networks, and ensemble methods.

## Dataset

The dataset (`Modi_Tweets.csv`) includes tweets with sentiment labels (-1, 0, 1) and text content. Initial preprocessing involves handling null values and converting categorical sentiment labels to integers for classification tasks.

## Models Implemented

### XGBoost Classifier

- Multi-class classification using XGBoost for sentiment prediction.
- TF-IDF vectors are used for feature representation.

### Random Forest Classifier

- Random Forest model for sentiment analysis.
- TF-IDF vectors are employed for text feature extraction.

### Gradient Boosting Classifier

- Gradient Boosting model for sentiment classification.
- Utilizes TF-IDF vectors for text representation.

### Support Vector Machine (SVM)

- SVM with linear kernel for sentiment prediction.
- TF-IDF vectors are used for text feature extraction.

### LSTM Neural Network

- Deep learning model with LSTM for sentiment analysis.
- Tokenization and word embeddings are used for text representation.

### Bagging and Boosting Techniques

- Bagging and Boosting techniques using XGBoost as base estimator.
- Ensemble methods are employed to enhance predictive performance.


