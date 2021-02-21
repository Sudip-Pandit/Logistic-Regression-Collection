# Logistic-Regression on::

# 1. Pima Dataset


# Introduction
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
Several constraints were placed on the selection of these instances from a larger database.
In particular, all patients here are females at least 21 years old of Pima Indian heritage.

# Description of the dataset
The datasets consists of several medical predictor variables and one target variable, Outcome.
Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.


# logistic regression on admission dataset:
# Description of the Project
Importing the Libraries and load the datasets
Exploring the data and visualization
Train and create logistic regression model
Evaluation of model(Precision, recall and F1 score), Confusion Matrix
Model Improvements

# Introdcution:
Regression analysis is used to predict the dependent variable based on the basis of one or more independent varibales. It explains the predict/impact of changes in the independent attributes on the dependent variable. The Logistic regression, also called a logit model, is used to model dichotomous outcome variables. In the logit model, the log odds of the outcome is modeled as a linear combination of the predictor variables.

# Description of the data
I have collected this data from the URL-https://stats.idre.ucla.edu/ of Institute of Digital Research and Statistical Consulting. This datasets has the following features:- gre, gpa and rank (There are three predictor variables: gre, gpa and rank). The dependent variable is admit which has two classes 1 and 0. If he/she admits then assigned 1, if he/she not admit then assigned 0.

# Evaluation
This project is based on how independent variables such as GRE (Graduate Record Exam scores), GPA (grade point average) and prestige of the undergraduate institution would effect on admission into graduate school. The target variable is binay .i.e. either that student will be going to admit the school or not. After the preprocessing of the data, EDA and generate x and y variables, I built a Logistic regression model, which is checked by confusion_matrix and classification report.
