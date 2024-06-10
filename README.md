Fake News Detection Using Machine Learning

Overview

This project aims to classify news articles as either fake or real based on their text content. We employed several machine learning models to achieve this classification task: Naive Bayes, Logistic Regression, Decision Tree, and Random Forest. The project includes data preprocessing steps, exploratory data analysis, and model evaluation.

Introduction
Fake news detection is an important task in today's digital age where information is disseminated at a rapid pace. The goal is to build models that can accurately distinguish between fake and real news articles using text classification techniques.

Dataset

The dataset used in this project consists of two CSV files: Fake.csv and True.csv. Each file contains news articles labeled as fake or true.

Fake.csv: Contains fake news articles.
True.csv: Contains real news articles.

Data Preprocessing

Data preprocessing steps include:

Concatenating the fake and real news datasets.
Shuffling and resetting the index.
Dropping irrelevant columns such as date and title.
Converting text to lowercase.
Removing punctuation and stopwords.

Exploratory Data Analysis

We performed basic data exploration to understand the distribution of the data. This included:

Counting the number of articles per subject.
Counting the number of fake and real articles.
Visualizing the most frequent words in fake and real news articles using WordCloud.

Models

We used the following machine learning models for fake news detection:

Naive Bayes
Logistic Regression
Decision Tree
Random Forest
Each model was implemented using a pipeline that included CountVectorizer and TfidfTransformer for text preprocessing.

Results

The performance of each model was evaluated using accuracy and confusion matrix. The accuracies of the models are as follows:

Naive Bayes: 95.28%
Logistic Regression: 98.84%
Decision Tree: 99.67%
Random Forest: 99.10%
Decision Tree achieved the highest accuracy, followed closely by Logistic Regression and Random Forest.

Conclusion

All models performed exceptionally well in classifying fake and real news articles. The Decision Tree model achieved the highest accuracy and is recommended for this task due to its ability to capture complex relationships in the data.
