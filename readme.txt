# Sentiment Analysis Using Natural Language Processing

## Overview
This project focuses on sentiment analysis using Natural Language Processing (NLP). The dataset used is a collection of restaurant reviews (`Reviews_Restaurant.tsv`). The goal is to classify reviews as positive or negative based on their content.

## Prerequisites
- Python
- Required libraries (Pandas, NumPy, Matplotlib, NLTK, Scikit-learn)

## Dataset
The dataset that is used - `Reviews_Restaurant.tsv`. It contains reviews and corresponding labels (Liked or Not Liked).

## Data Preprocessing
- The reviews are cleaned by removing URLs, special characters, and numbers.
- Text is lowercased, tokenized, and stopwords are removed.
- Lemmatization is applied to transform words to their base form.

## Bag of Words Model
- The Bag of Words model is created using the CountVectorizer with a maximum of 3000 features.
- The dataset is split into training and testing sets.

## Naive Bayes Model
- A Multinomial Naive Bayes classifier is trained on the training set.
- Predictions are made on the test set.

## Evaluation Metrics
- Accuracy, classification report, and confusion matrix are presented for model evaluation.
- Error analysis is performed to identify misclassified samples.

## Hyperparameter Tuning
- Grid search is used to tune hyperparameters for the Naive Bayes model.
- Precision-recall curve, ROC curve, and AUC are visualized.

## Confusion Matrix Visualization
- The confusion matrix is visualized using a heatmap.

## How to Run
1. Ensure Python is installed.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `sentiment_analysis_nlp.py` script.

## Results
- Text reviews are classified as either positive or negative(1) or negative (0)
- Model performance metrics and visualizations are presented.


