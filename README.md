# BISI-CST2101-W23-Project

## Description

Welcome to CST2101 Project. In this project, we aim to analyze diabetes data and address some important business problems/questions. This project is focused on Exploratory Data Analysis and Model Training using Python.

## Problem Statement

Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe (also known as the Pima Indians). In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima Indian heritage.

## Objective

Here, we are analyzing different aspects of Diabetes in the Pima Indians tribe by doing Exploratory Data Analysis and building a classification Model.

## Dataset Information

Below is the attribute information:

* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* Blood pressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skinfold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml) test
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: A function that scores likelihood of diabetes based on family history
* Age: Age in years
* Outcome: Class variable (0: the person is not diabetic or 1: the person is diabetic)

#### Libraries

pandas, seaborn, matplotlib, sklearn.

## Models

### Logistic Regression

Logistic regression is a popular machine learning model used for binary classification tasks. It is a supervised learning algorithm that works by learning a decision boundary to separate data into two classes based on a set of input features.

The model uses the same logistic function as in statistical logistic regression to estimate the probability of a binary outcome. It then makes a prediction by classifying an observation into one of two classes based on a decision boundary, typically set at 0.5.

Logistic regression is a linear model, which means it assumes a linear relationship between the input features and the output variable. However, this assumption can be relaxed by using techniques such as polynomial regression or feature engineering.

Logistic regression has several advantages as a machine learning model. It is simple, fast, and easy to interpret, making it suitable for small datasets and situations where interpretability is important. It can also handle noisy data and can be regularized to prevent overfitting.

Overall, logistic regression is a versatile machine learning model that can be used for a variety of binary classification tasks, including spam filtering, fraud detection, and disease diagnosis.


<img src="https://tutorialforbeginner.com/images/tutorial/logistic-regression-in-machine-learning.png">

### Random Forrest

Random Forest is a popular and powerful ensemble machine learning algorithm that combines multiple decision trees to make more accurate predictions. In a random forest, each tree is trained on a different subset of the data, and the final prediction is made by aggregating the predictions of all the trees.

The "random" in random forest comes from two main sources. First, the subset of data used to train each tree is randomly sampled from the original data set. This helps to reduce overfitting and improve the model's generalization performance. Second, at each split in a decision tree, a random subset of features is considered as candidates for the best split. This randomness further helps to reduce correlation among the trees and improve the overall model's robustness.

Random forests can be used for both regression and classification tasks, and they are particularly useful for high-dimensional data with many features. They are also able to handle missing data and maintain good performance even in the presence of noise or outliers.

Overall, random forest is a versatile and powerful machine learning algorithm that has proven to be effective in a wide range of applications.

<img src="https://lh4.googleusercontent.com/ANxp1CRZ8m4UohG8XJpvJusOpP-v-_7JLVwXXCpOAWwxdH2cEq0LRUym6WZgkdJNukBhUjCdBwnVYGm-gqXAn6YIEYM96CUbOHr0JhEAWawyygy5mShAiny3IRcdYmA63sxz26pT">


## Usage

* Download the code zip file from the github repository: https://github.com/kris0107/BISI-CST2101-W23-Project
* Use Anaconda Navigator (Anaconda3) to open the ipynb file in jupyter notebook and run all cells.
