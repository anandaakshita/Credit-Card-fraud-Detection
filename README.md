<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Credit Card Fraud Detection</title>
    <style>
        pre {
            background-color: #f8f8f8;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <h1>Credit Card Fraud Detection using Machine Learning</h1>
    <p>This repository contains a Credit Card Fraud Detection algorithm using machine learning techniques in Python.</p>
    
    <h2>Credit Card Fraud Detection</h2>
    <p>With a lot of people, banks, and online retailers being victims of credit card fraud, a model detecting whether the transaction is fraud or not can help in saving a huge amount of money.</p>
    
    <h2>Dataset</h2>
    <p>The dataset has been obtained from Kaggle. This dataset contains 284,807 rows and 30 numeric columns and one class that specifies whether the transaction is fraudulent or not. The values of columns V1-V28 in the dataset may be the result of a PCA (Principal Component Analysis) Dimensionality reduction to protect user identities and sensitive information. There are no missing values in the dataset.</p>
    <p>You can find the dataset at the following link: <a href="https://www.kaggle.com/mlg-ulb/creditcardfraud" target="_blank">Credit Card Fraud Dataset on Kaggle</a></p>
    
    <h2>Algorithm</h2>
    <p>The algorithm used in this dataset is the Random Forest algorithm. For model improvement, normalization and SMOTE techniques (to handle imbalanced data) were used.</p>
    
    <h2>Visualization</h2>
    <p>The library used for visualizing the data, confusion matrix, etc. is seaborn.</p>
    
    <h2>Development</h2>
    <p>This code is prepared using Jupyter Notebook.</p>
</body>
</html>
