# Movie Genre Classification using Machine Learning Models
This repository contains a project that focuses on classifying movie genres using various machine learning models, including Naive Bayes, Logistic Regression, and Support Vector Machines (SVM). The goal of this project is to demonstrate how different machine learning algorithms can be used to predict the genre of a movie based on its textual features.

## Table of Contents
- Introduction
- Data
- Machine Learning Models
- Usage
- Results
- Contributing
- License

## Introduction
Movie genre classification is a popular problem in natural language processing and machine learning. It involves predicting the genre(s) of a movie based on its plot summary, cast, and other textual features. Accurate genre classification can be used to improve movie recommendation systems and help users discover movies they might enjoy.

In this project, we explore the use of three popular machine learning algorithms for movie genre classification: Naive Bayes, Logistic Regression, and Support Vector Machines. We preprocess the textual data, train and evaluate these models, and compare their performance.

## Data
We used a publicly available dataset containing movie information, including movie titles, plot summaries, and genre labels. You can find the dataset used in this project in the data directory. The dataset is already preprocessed and split into training and testing sets for your convenience.

## Machine Learning Models
### Naive Bayes
Naive Bayes is a simple yet effective algorithm for text classification. We implemented a Multinomial Naive Bayes classifier for movie genre classification.

### Logistic Regression
Logistic Regression is a commonly used algorithm for binary and multiclass classification. We trained a Logistic Regression model to predict movie genres.

### Support Vector Machines
Support Vector Machines (SVM) are powerful models for classification tasks. We used the Scikit-Learn library to build an SVM classifier for movie genre classification.
