# Spam Classification

## Table of Contents
[About](#about) <br>
[Dataset](#data) <br>
[Data Preprocessing](#preprocess) <br>
[Modelling](#model) <br>
[Model Evaluation](#eval) <br>
[Dependencies](#dependencies) <br>

<a name="about"></a>
## About
A project to classify emails as spam or not-spam based on their contents. Using the UCI Machine Learning Repository's Spambase dataset.
Dataset is available at https://archive.ics.uci.edu/ml/datasets/Spambase

<a name="data"></a>
## Dataset
The dataset used for this project is the UCI Machine Learning Repository's Spambase dataset, available at https://archive.ics.uci.edu/ml/datasets/Spambase. 
It consists of various attributes related to emails, including word frequency, character frequency, and capital letter run length and 
also a binary spam attribute indicating if an email is considered spam or not. <br>
More information can be found in the spambase.DOCUMENTATION file.

<a name="preprocess"></a>
## Data Preprocessing
The data preprocessing steps that were performed on the dataset include:
- Duplicate Removal
- Dealing with Null Values
- Fixing Data Imbalances
- Data Training & Testing Split
- Data Standardization
- Feature Selection

<a name="model"></a>
## Modelling
The 2 machine learning models used for this project were K Nearest Neighbors (KNN) and Decision Trees.

<a name="eval"></a>
## Model Evaluation

<a name="dependencies"></a>
## Dependencies
The following libraries were used in the project:
- scikit-learn
- pandas
- seaborn
- matplotlib
- imblearn
- collections

<a name="results"></a>
## Results
