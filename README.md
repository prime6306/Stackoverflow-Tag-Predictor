## Multi-Label Text Classification & Preprocessing

This project focuses on preprocessing text data and applying multi-label classification techniques using machine learning models. The notebook includes data handling, database integration, feature extraction, and classification approaches for text datasets.

# 🚀 Features

Data Preprocessing

Cleaning and preparing text using regex.

Tokenization and vectorization (CountVectorizer).

Generating WordClouds for visualization.

Database Integration

Functions to connect, create tables, and check for existence.

Multi-Label Classification

# Models:

Logistic Regression

Gaussian Naive Bayes

Binary Relevance (from scikit-multilearn)

Classifier Chains

# Visualization

Data exploration with Seaborn and WordCloud.

Utility Functions

Tag selection (tags_to_choose)

Question explanations (questions_explained_fn)

#📂 Project Structure

main.ipynb → Jupyter Notebook with all preprocessing, modeling, and evaluation steps.

Database-related functions:

create_connection

create_table

checkTableExists

create_database_table

Machine learning functions:

tags_to_choose

questions_explained_fn

#🛠️ Requirements

Install dependencies with:

pip install -r requirements.txt


# Main Libraries Used:

numpy

pandas

scikit-learn

scikit-multilearn

seaborn

matplotlib

wordcloud

re

datetime

# Usage

Open the Jupyter Notebook:

jupyter notebook main.ipynb


Run the cells step by step:

Preprocessing and cleaning data.

Database creation and storage.

Model training and evaluation.

Visualization of results.

Modify configurations (e.g., choice of classifier, parameters) as needed.



Evaluate performance with accuracy, precision, recall, and micro F1 score.

