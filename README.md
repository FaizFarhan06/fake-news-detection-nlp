# Fake News Detection with NLP

A text classification project for detecting whether a news article is real or fake.

## Overview

This project uses Natural Language Processing (NLP) and machine learning to classify news articles based on their text.

The dataset contains separate collections of real and fake news. The two datasets are combined and labeled before being used for model training.

## Process

1. Load the real and fake news datasets
2. Combine and label the data
3. Clean and preprocess the article text
4. Remove stopwords and apply stemming
5. Convert text into numerical features using TF-IDF
6. Split the data into training and testing sets
7. Train the classification model
8. Evaluate the model using a confusion matrix
9. Save the trained model and TF-IDF vectorizer

## Files

* `main.ipynb` — data processing, model training, and evaluation
* `data/` — dataset files
* `model2.pkl` — trained classification model
* `tfidfvect2.pkl` — fitted TF-IDF vectorizer

## Tools

* Python
* Pandas
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn

## Prediction

The trained model can be used to classify new text as:

* `FAKE`
* `REAL`

## Notes

This project focuses on the text classification process and is intended as a machine learning and NLP project.
