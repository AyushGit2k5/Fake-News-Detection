# Fake News Detection

## Problem
Built a binary text classification system to automatically detect fake news articles and distinguish them from real news content.

## Dataset
Used a public fake news dataset consisting of labeled news articles (real vs fake). The dataset contains textual news content with overlapping linguistic patterns between classes.

## Approach
Implemented and compared two classical NLP baselines:
- TF-IDF with Multinomial Naive Bayes
- TF-IDF with Logistic Regression  

Both models were trained using identical preprocessing pipelines to ensure a fair comparison.

## Evaluation
Models were evaluated using accuracy, precision, recall, F1-score, and confusion matrices on a held-out test set.

## Results
Logistic Regression achieved stronger overall performance than Naive Bayes, demonstrating better separation of overlapping language patterns in real and fake news articles.

## Future Improvements
Potential improvements include n-gram tuning, improved text preprocessing, handling class imbalance, and experimenting with transformer-based models for richer contextual understanding.
