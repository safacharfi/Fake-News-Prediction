# Fake News Prediction

This project aims to predict whether a news article is fake or real using machine learning techniques. We utilize TF-IDF (Term Frequency-Inverse Document Frequency) to convert textual data into numerical features and Logistic Regression to classify news articles.

## Introduction

In this project, we focus on classifying news articles as either fake or real. The approach involves:

1. **Preprocessing Text Data:** Transforming news articles into numerical data using TF-IDF.
2. **Model Training:** Using Logistic Regression to train the model on the processed data.
3. **Evaluation:** Assessing the model's performance to ensure accurate predictions.

## Features

- Text preprocessing using TF-IDF.
- Logistic Regression for classification.
- Evaluation metrics for model performance (e.g., accuracy, precision, recall).

## Training the Model

The model is trained using a dataset of news articles. The training process involves:

1. **Data Loading:** Reading the dataset and splitting it into training and testing sets.
2. **Text Vectorization:** Converting news articles into TF-IDF features.
3. **Model Training:** Training the Logistic Regression model on the TF-IDF features.
4. **Model Saving:** Saving the trained model for future use.




