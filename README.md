# Text Classification Using Natural Language Processing

## Overview
This repository contains a postgraduate-level natural language processing (NLP) capstone project focused on classifying short text messages as spam or non-spam. The project demonstrates a complete NLP pipeline using Python, from text preprocessing to model evaluation.

## Objective
The objective of this project is to apply classical NLP techniques to build and evaluate a machine learning model for text classification using real-world data.

## Dataset
The analysis uses the **SMS Spam Collection Dataset** from the UCI Machine Learning Repository.

- Source: https://archive.ics.uci.edu/ml/datasets/sms+spam+collection
- Format: Text (tab-separated)
- Classes: Spam, Ham (non-spam)

The dataset is publicly available and widely used for academic research.

## Methodology
The project follows a standard NLP workflow:
- Text preprocessing (lowercasing, noise removal)
- Feature extraction using TF-IDF
- Train–test split
- Classification using logistic regression
- Model evaluation using confusion matrix and classification metrics

## Tools and Technologies
- Python
- Google Colaboratory (Jupyter Notebook)
- pandas, NumPy
- scikit-learn
- TF-IDF Vectorization

## Results Summary
The logistic regression classifier achieved an accuracy of approximately 95%. The model demonstrated strong performance in identifying non-spam messages and high precision in spam detection, with some reduction in recall due to class imbalance.

## Limitations
- The model uses bag-of-words representations and does not capture semantic context.
- Class imbalance affects recall for spam messages.
- More advanced NLP models could further improve performance.


## Author
**Maureen Chepkirui**

