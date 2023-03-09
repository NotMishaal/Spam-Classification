# Spam Classification

## Table of Contents
[About](#about)
[Dataset](#data)
[Data Preprocessing](#preprocess)
[Modelling](#model)
[Model Evaluation](#eval)
[Dependencies](#dependencies)

<a name="about"/>
## About
A project to classify emails as spam or not-spam based on their contents. Using the UCI Machine Learning Repository's Spambase dataset.
Dataset is available at https://archive.ics.uci.edu/ml/datasets/Spambase

<a name="data"/>
## Dataset
The dataset used for this project is the UCI Machine Learning Repository's Spambase dataset, available at https://archive.ics.uci.edu/ml/datasets/Spambase. 
It consists of various attributes related to emails, including word frequency, character frequency, and capital letter run length and 
also a binary spam attribute indicating if an email is considered spam or not.
More information can be found in the spambase.DOCUMENTATION file.

<a name="preprocess"/>
## Data Preprocessing
The data preprocessing steps that were performed on the dataset include:
- Duplicate Removal
- Dealing with Null Values
- Fixing Data Imbalances
- Data Training & Testing Split
- Data Standardization
- Feature Selection

<a name="model"/>
## Modelling
The 2 machine learning models used for this project were K Nearest Neighbors (KNN) and Decision Trees.

<a name="eval"/>
## Model Evaluation

<a name="dependencies"/>
## Dependencies
The following libraries were used in the project:
- scikit-learn
- pandas
- seaborn
- matplotlib
- imblearn
- collections

<a name="results"/>
## Results
