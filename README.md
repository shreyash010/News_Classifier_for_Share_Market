# News Headlines Text Classification

## Overview

This project focuses on text classification using various machine learning models to predict the category of news headlines. The text preprocessing techniques, feature engineering, and the following classification models were implemented:

1. Logistic Regression
2. Linear Support Vector Classifier (LinearSVC)
3. Polynomial Support Vector Classifier (SVC)
4. Radial Basis Function Support Vector Classifier (SVC)

## Project Details

### Text Preprocessing

Text preprocessing is an important step to clean and prepare the data for machine learning. The following steps were performed on the news headlines:

1. Punctuation Removal: All punctuation marks were removed to clean the text data.
2. Stopword Removal: Common stopwords were removed to reduce noise in the text.
3. Lemmatization: Text was lemmatized to normalize words to their base forms.

### Feature Engineering

To convert the text data into a format suitable for machine learning models, we used TF-IDF vectorization. The TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer was applied to transform the text into numerical features.

### Classification Models

We implemented several classification models to predict the category of news headlines. The models were trained on the preprocessed and TF-IDF transformed data. The accuracy of these models is as follows:

- Logistic Regression: 78.12%
- Linear Support Vector Classifier (LinearSVC): 79.77%
- Polynomial Support Vector Classifier (SVC)
- Radial Basis Function Support Vector Classifier (SVC)

## Getting Started

### Prerequisites

To run this project, you'll need Python and the following libraries:

- scikit-learn
- nltk
- pandas
- numpy

You can install these libraries using pip:

```bash
pip install scikit-learn nltk pandas numpy
