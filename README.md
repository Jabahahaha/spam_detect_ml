# Spam vs Ham Text Classifier

A simple machine learning project that classifies SMS messages as spam or ham (not spam) using text classification techniques.

## Overview

This project implements a binary text classifier using the SMS Spam Collection dataset. The goal is to learn and practice basic NLP techniques including text preprocessing, feature extraction with TF-IDF, and training classification models.

## Dataset

The project uses the SMS Spam Collection dataset which contains:
- 4,825 ham (normal) messages
- 747 spam messages

## Features

- Simple text preprocessing (lowercase, punctuation removal)
- TF-IDF feature extraction
- Logistic Regression classifier
- Model evaluation with accuracy, precision, recall, and F1 score
- Experimentation with unigrams vs bigrams

## Requirements

Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook spam_classifier.ipynb
```

2. Run all cells to see the complete workflow from data loading to model evaluation.

## Results

The model achieves:
- **Accuracy**: ~96.9%
- **Precision**: 100%
- **Recall**: ~77%
- **F1 Score**: ~87%

## Project Structure

```
spam_detect_ml/
├── spam.csv                 # Dataset
├── spam_classifier.ipynb    # Main notebook
├── requirements.txt         # Python dependencies
└── README.md               # This file
```

## What I Learned

- How to preprocess text data for machine learning
- Using TF-IDF for feature extraction
- Training and evaluating text classification models
- The importance of proper train/test splits

## Future Improvements

- Try other classifiers (Naive Bayes, SVM, etc.)
- Experiment with different preprocessing techniques
- Add cross-validation for more robust evaluation
- Handle class imbalance if needed
