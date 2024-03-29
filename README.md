# Credit_Card_Fraud_Detection

This project mainly focuses on handling imbalanced datasets and detecting credit-card frauds using Following Machine Learning Algorithms:

a) Logistic Regression

b) RandomForestClassifier

c) DecisionTreeClassifier

d) XGBCLassifier

e) KNeighbors Classifier

f) GaussianNB 


These models are fittted to different datasets acquired after StandardScaler, Oversampling, Undersampling and SMOTE techniques. Thus, separate files are created for each Machine Learning Models so that every datasets acquired after above mentioned techniques are fitted separately to our model using single function.


ABOUT DATASETS:

URL : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This datasets have 492 frauds out of 284,807 transactions. It is highly unbalanced, the positive class--1 (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features are not provided and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

Feature Time contains the seconds elapsed between each transaction and the first transaction in the dataset.But, we did not consider Time for training purpose as it is of no use to build the models and may not impact our target variable.

The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.

Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.


# STEPS : 

1) Importing Libraries & Loading Datasets.

2) Data Preprocessing & Preparing Datasets.

3) Exploratoty Data Analysis(EDA) & Visualization.

4) Handling Imbalanced Datasets. 

5) Conclusions.



# Conclusions:

a) Out of all 6 Machine Learning Models used, Random Forest Classifier works efficiently with Maximum Accuracy of 99.996483% and macro-average of F1-Score of 1.00 acheived with Oversampling technique.

b) Oversampling Techniques proved to be efficient for handling Imbalanced Datasets.

c) RandomForest, XGBoost, DecisionTree, K-Neighbors work efficiently even for this Imbalanced Datasets.

d) RandomForest takes lots of Training Time among all of Six models used.


