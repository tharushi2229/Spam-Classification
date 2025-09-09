# SMS Spam Classifier

A machine learning project that automatically classifies SMS messages as spam or legitimate (ham) using Natural Language Processing techniques.

## Overview

This project implements a spam detection system using the Naive Bayes algorithm with TF-IDF feature extraction. The model analyzes text patterns in SMS messages to determine whether they are spam or not.

## Features

- **Data Preprocessing**: Cleans and prepares SMS text data
- **Text Processing**: Lowercasing, tokenization, stopword removal, and stemming
- **Feature Extraction**: Uses TF-IDF vectorization to convert text to numerical features
- **Machine Learning**: Implements Multinomial Naive Bayes classifier
- **Data Visualization**: Analyzes message length distribution by class

## Dataset

The project uses a spam SMS dataset (`spam.csv`) containing:
- SMS messages
- Labels (spam/ham)
- Additional preprocessing for duplicate removal

## Key Technologies

- **Python Libraries**: pandas, nltk, scikit-learn
- **NLP Techniques**: Porter Stemming, Stopword Removal, Tokenization
- **ML Algorithm**: Multinomial Naive Bayes
- **Feature Engineering**: TF-IDF Vectorization

## Workflow

1. **Data Loading**: Import and explore the SMS dataset
2. **Data Cleaning**: Remove duplicates and unnecessary columns
3. **Text Preprocessing**: Clean and normalize text data
4. **Feature Extraction**: Convert text to numerical features using TF-IDF
5. **Model Training**: Train Naive Bayes classifier
6. **Evaluation**: Test model accuracy on unseen data

## Results

The model achieves high accuracy in distinguishing between spam and legitimate SMS messages, making it suitable for real-world spam filtering applications.

## Usage

Run the Jupyter notebook to train the model and evaluate its performance on SMS spam detection.
