Fake News Detection Internship - CodeClause
Fake News Detection

Introduction
This repository contains the code and resources for my internship project with CodeClause on Fake News Detection using Jupyter Notebook. The goal of this project was to develop a machine-learning model that predicts whether a news article is fake or genuine. The dataset used for training the model was obtained from Kaggle.

Requirements
Python 3.x
Jupyter Notebook
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Model Details
The model for fake news detection was built using the Jupyter Notebook environment and Python programming language. The main steps of the project include:

Data Cleaning and Preprocessing: Removing irrelevant information, handling missing values, and text preprocessing (e.g., lowercasing, removing special characters, stopwords, etc.).

Text Vectorization: Transforming the preprocessed text into numerical feature vectors using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

Model Selection: Four different classifiers were used in this project for fake news detection:

Random Forest Classifier with an accuracy of 98.62%
Gradient Boosting Classifier with an accuracy of 99.5%
Decision Tree Classifier with an accuracy of 99.5%
Logistic Regression Classifier with an accuracy of 99.1%
Model Ensemble: The final output was improved by combining the predictions of all four classifiers using an ensemble method (e.g., Voting Classifier or Stacking).

Results
The developed ensemble model achieved an overall accuracy of more than 99% in predicting whether a news article is fake or genuine. The high accuracy demonstrates the effectiveness of combining multiple classifiers to make accurate predictions.
