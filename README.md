# Spam Classification
<a name="about"></a>
## About
A project to classify emails as spam or not-spam based on their contents. Using different machine learning algorithms, applied on the UCI Machine Learning Repository's Spambase dataset.

## Table of Contents
1. [About](#about) <br>
2. [Dataset](#data) <br>
3. [Data Preprocessing](#preprocess) <br>
4. [Modelling](#model) <br>
5. [Model Evaluation](#eval) <br>
6. [Dependencies](#dependencies) <br>

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
### KNN
|     | precision   |   recall |   f1-score |   support |
|---: |:-----------:|:--------:|:----------:|:---------:|
|  0  |        0.93 |     0.93 |       0.93 |       604 |
|  1  |        0.94 |     0.94 |       0.94 |       662 |
|     |             |          |            |           |
|accuracy|          |          |       0.93 |      1266 |
|macro avg|    0.93 |     0.93 |       0.93 |      1266 |
|weighted avg| 0.93 |     0.93 |       0.93 |      1266 |

### DT
|     | precision   |   recall |   f1-score |   support |
|---: |:-----------:|:--------:|:----------:|:---------:|
|  0  |        0.88 |     0.95 |       0.92 |       604 |
|  1  |        0.95 |     0.88 |       0.92 |       662 |
|     |             |          |            |           |
|accuracy|          |          |       0.92 |      1266 |
|macro avg|    0.92 |     0.92 |       0.92 |      1266 |
|weighted avg| 0.92 |     0.92 |       0.92 |      1266 |

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
While the Decision Tree model did outperform the KNN model in some metrics, such as recall of non-spam and precision of spam. Overall the KNN model proved to have the better overall performance when it came to the evaluation.
