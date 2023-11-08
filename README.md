# Credit Card Fraud Detection

This project aims to detect credit card fraud using machine learning techniques. We utilize a real dataset containing information about credit card transactions made by European cardholders in September 2013. The goal is to build a model that can determine the legitimacy of a credit card transaction.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Import](#data-import)
3. [Data Preprocessing](#data-preprocessing)
   - [Handling Outliers](#handling-outliers)
   - [Data Imbalance](#data-imbalance)
4. [Model Building](#model-building)
   - [Random Forest Classifier](#random-forest-classifier)
5. [Model Evaluation](#model-evaluation)
   - [On Imbalanced Data](#on-imbalanced-data)
   - [On Balanced Data](#on-balanced-data)
6. [Conclusion](#conclusion)

## Introduction

In this project, we aim to detect credit card fraud using machine learning models. The dataset includes transactions made by European cardholders in September 2013. We will train models to classify transactions as either legitimate or fraudulent.

## Data Import

We import the dataset from the following [GitHub link](https://raw.githubusercontent.com/nsethi31/Kaggle-Data-Credit-Card-Fraud-Detection/master/creditcard.csv) and load it into a Pandas DataFrame.

## Data Preprocessing

### Handling Outliers

We detect and remove outliers from the dataset, focusing on columns such as 'V1' to ensure data quality.

### Data Imbalance

We address data imbalance by oversampling the minority class using the Synthetic Minority Over-sampling Technique (SMOTE).

## Model Building

We create a Random Forest Classifier model to classify transactions as legitimate or fraudulent.

### Random Forest Classifier

We utilize the Random Forest Classifier to build our predictive model. This model is trained on the preprocessed data to make predictions.

## Model Evaluation

### On Imbalanced Data

We evaluate the model's performance on the original imbalanced dataset, highlighting the need for improved recall and F1-score.

### On Balanced Data

We assess the model's performance on the balanced dataset, which demonstrates improvements in accuracy and precision.

## Conclusion

This project showcases the process of detecting credit card fraud using machine learning techniques. By addressing data imbalance and preprocessing the data, we can improve the model's performance in identifying fraudulent transactions.

For a detailed code implementation, please refer to the [Jupyter Notebook](https://colab.research.google.com/drive/1bjTlzW8k-CWbqqjcZTgalrZU6e7uF9Py) associated with this project.

---

Feel free to use this markdown template for your README.md file on GitHub. You can copy and paste it into your repository and customize it further as needed. If you have any additional information or requirements, please let me know, and I'll be happy to assist further.
