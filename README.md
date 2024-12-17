# IMDB Movie Sentiment Analysis

## Overview

The **IMDB Movie Sentiment Analysis** project implements a sentiment analysis model on a dataset of 50,000 movie reviews from the Internet Movie Database (IMDB). The dataset is balanced with an equal number of positive and negative reviews. This project aims to classify the sentiment of movie reviews using various machine learning techniques and natural language processing (NLP) methods.

## Technologies Used

- **Python**: The primary programming language used for implementation.
- **NLTK**: Natural Language Toolkit for text preprocessing and analysis.
- **Scikit-learn**: A machine learning library for model training and evaluation.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.

## Features

- **Dataset**: Utilizes a balanced dataset of 50,000 movie reviews from IMDB, with equal representation of positive and negative sentiments.
- **Text Preprocessing**:
  - Vectorization of text data.
  - Stop-word removal to eliminate common words that do not contribute to sentiment.
  - Lemmatization to reduce words to their base or root form.
  - N-gram analysis to capture context and improve model performance.
- **Modeling**:
  - Implemented various models including:
    - Logistic Regression
    - Linear Support Vector Classification (LinearSVC)
  - Achieved over 90% accuracy in sentiment classification.
