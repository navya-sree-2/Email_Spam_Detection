# Email Spam Detection

This project builds a machine learning model to classify emails as spam or not spam using the `Spam.csv` dataset.

## Overview

- **Dataset**: Contains email messages labeled as spam (`0`) or ham (`1`).
- **Preprocessing**: 
  - Checked for missing values (none found).
  - Labeled spam as `0` and ham as `1`.
  - Removed duplicate rows.
- **Feature Extraction**: Used **TF-IDF Vectorization** to transform the text data into numerical form.
- **Models Used**: 
  - Logistic Regression
  - Support Vector Classifier (SVC)
- **Evaluation**: The models were evaluated using accuracy, classification report, and confusion matrix.

## Results

The model performed well in classifying spam and ham emails based on the dataset provided.
