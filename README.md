# Campus-Recruitment-Prediction
Campus recruitment is a strategy for sourcing, engaging and hiring young talent for internship and entry-level positions. The model is to predict the placement of students based on their specialisation, SSLC percentage, experience &amp; other 12 features. 

The recruiting team commonly considers university or college rankings provided by external agencies for fresh talent hiring. Different companies’ demands are different in the time of recruiting but while recruiting fresh graduates, they focus on some particular fields by which they find out which candidate they want for their work. The fields based on which companies are recruiting fresh graduates are analyzed using several machine learning techniques and predicted the possible fields.

In this work, different supervised machine learning techniques have been used for classification of Campus Recruitment data set and the classification of these techniques have been compared with each other using the values of accuracy and Confusion Matrix.

## About DataSet

Source: https://www.kaggle.com/benroshan/factors-affecting-campus-placement

This data set consists of Placement data of students in campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students

## Feature Selection

Numerical data - ExtraTreesClassifier 

Categorical data - chi2_contingency

## ML Models Used

CatBoostClassifier,
Logistic Regression,
Support Vector Machine,
Decision Tree,
Neural Network,
Random Forest,
XGBoost,
LGBMClassifier,
XGBRFClassifier,
GradientBoosting,
GaussianNB,
KNeighborsClassifier.

# Results-

![Untitled](https://user-images.githubusercontent.com/85584749/129434106-52a0b165-351e-4bac-9593-b0287ffa82cb.png)

## Sorted BarPlot of Accuracy

![Untitled](https://user-images.githubusercontent.com/85584749/129434150-49f0e232-e2fd-4bbb-8d95-674bbc48da2a.png)
