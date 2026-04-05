# Fake News Detection (NLP)

## Problem
Developed a binary text classification system to identify fake news articles and distinguish them from real news content.

## Dataset
Used a public fake news dataset consisting of labeled news articles (real vs fake). The dataset contains textual content with overlapping linguistic patterns, making classification non-trivial.

## Approach
- Applied TF-IDF vectorization to convert text data into numerical features.  
- Implemented and compared two baseline models:
  - Multinomial Naive Bayes  
  - Logistic Regression  
- Used a consistent preprocessing pipeline (text cleaning, tokenization, TF-IDF) across both models to ensure fair comparison.  

## Evaluation
Evaluated models on a held-out test set using accuracy, precision, recall, F1-score, and confusion matrices.

## Results
Logistic Regression outperformed Naive Bayes across all evaluation metrics, achieving higher accuracy and F1-score, indicating better handling of overlapping and sparse textual features.

## Key Learnings
- Linear models such as Logistic Regression perform strongly on TF-IDF representations for text classification tasks.  
- Naive Bayes provides a fast baseline but may struggle with complex language patterns.  

## Future Improvements
- Experiment with n-grams and feature tuning  
- Improve preprocessing (e.g., stopword handling, normalization)

## Visualizations
- Confusion matrices for both models  
- Bar chart comparing accuracy, precision, recall, and F1-score  
- Explore advanced models such as transformer-based architectures (e.g., BERT)  
