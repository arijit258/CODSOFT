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
https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

## Machine Learning Models
### Naive Bayes
Naive Bayes is a simple yet effective algorithm for text classification. We implemented a Multinomial Naive Bayes classifier for movie genre classification.

### Logistic Regression
Logistic Regression is a commonly used algorithm for binary and multiclass classification. We trained a Logistic Regression model to predict movie genres.

### Support Vector Machines
Support Vector Machines (SVM) are powerful models for classification tasks. We used the Scikit-Learn library to build an SVM classifier for movie genre classification.

## Images

### 1. Countplot of Genre
![Image-1](https://github.com/arijit258/CODSOFT/blob/main/Movie_Genre_Classification/training_data_genre_distribution.png)

### 2. Barplot of Genre
![image-2](https://github.com/arijit258/CODSOFT/blob/main/Movie_Genre_Classification/training_data_genre_distribution_barplot.png)


## Usage
To run this project, follow these steps:

### 1. Clone this repository to your local machine:

`git clone https://github.com/your-username/movie-genre-classification.git`
`cd Movie_Genre_Classification`

### 2. Install the required Python packages. You can use a virtual environment to manage dependencies.
`pip install -r requirements.txt`


### 3. Run the Jupyter notebooks in the notebooks directory to train and evaluate the machine learning models.

### 4. Experiment with different hyperparameters, feature extraction techniques, and text preprocessing methods to improve model performance.

### 5. Share your findings and contribute to the project.

### 6. Results
