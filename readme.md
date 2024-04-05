# Email Spam Detector 

## Overview
This project utilizes machine learning techniques to classify emails as either spam or not spam (ham). It employs a Naive Bayes classifier trained on a dataset of labeled emails to make predictions on new email inputs.

## Dataset
The dataset used for training the classifier is sourced from spam.csv, containing email samples labeled as 'spam' or 'ham' (not spam). This dataset is preprocessed to select relevant columns and convert labels to binary format (spam: 1, ham: 0).

## Methodology
Data Preprocessing: Relevant columns are selected, and labels are converted to binary format.
Feature Extraction: Text data is converted into numerical feature vectors using Count Vectorization.
Model Training: A Multinomial Naive Bayes classifier is trained on the vectorized features.
GUI Development: A simple GUI (Graphical User Interface) using tkinter is created to input new email text for classification.
Classification: Upon user input, the trained model predicts whether the email is spam or not spam, and the result is displayed using a message box.

## Dependencies
pandas for data manipulation.
scikit-learn for machine learning functionalities.
tkinter for building the GUI.


![spam img](https://github.com/Husniahmed10/Email-Spam-Detector/assets/141121519/da3dbb0d-04c1-447e-bab0-d47918f6ce96)
