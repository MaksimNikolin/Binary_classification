_**date of creation: September, 2023**_

## Problem:
To see which ML-algorithms give the best results for the credit scoring problem. The essence of the credit scoring task is: true or false a bank will issue a credit to a client, given input data about the client: name, gender, age, income, etc. Since the answer to the question is a yes/no answer, then we have a classification task before us.

## Dataset:
Dataset taken from Kaggle: [dataset here](kaggle/input/credit-scoring-dataset/train.csv). It is a table with dimensions (261384 x 122).

## Model:
First, the task involves processing the input data, the so-called _EDA_ (data is brought to the required form for work, gaps are removed, categorical ones are replaced with numeric ones, non-informational features are removed, classes are rebalanced).
Demonstration of the most popular ML-algorithms: _Logistic Regression, Random Forest, Boostings algoritms, SVM, Neural Network, KNN, Bayes_.

## Results:
On this data, the best results were obtained by the following algorithms: _Random Forest, LGBM, GBoost_.
