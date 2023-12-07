Task:
To see which ML-algorithms give the best results for the credit scoring problem. The essence of the credit scoring task is: true or false a bank will issue a credit to a client, given input data about the client: name, gender, age, income, etc. Since the answer to the question is a yes/no answer, then we have a classification task before us.
Dataset:
Dataset taken from Kaggle: kaggle/input/credit-scoring-dataset/train.csv. It is a table with dimensions (261384 x 122).
Model:
First, the task involves processing the input data, the so-called EDA (data is brought to the required form for work, gaps are removed, categorical ones are replaced with numeric ones, non-informational features are removed, classes are rebalanced).
Demonstration of the most popular ML-algorithms: Logistic Regression, Random Forest, Boostings algoritms, SVM, Neural Network, KNN, Bayes.
Results:
On this data, the best results were obtained by the following algorithms: Random Forest, LGBM, GBoost.
