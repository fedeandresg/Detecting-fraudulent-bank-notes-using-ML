![Logo](https://s44650.pcdn.co/wp-content/uploads/2023/07/open-banking-1200-1662083126-1.jpg)

# DATA SCIENCE - Detecting fradulent bank notes using ML
# Machine Learning

In this project, I will try to classify the bank notes as genuine or fake through **`ML algorithms`**.

Also I will analize the data for a better project.

For that purpose, I'm going to use a dataset from UCI Machine Learning.

## Context

There is a need to identify the veracity or falsity of the statistical data in the bank notes report.

It is recommended that models be defined to verify whether the new data to be entered can be classified as genuine (1) or false (0).

## Dataset

The [dataset](https://github.com/fedeandresg/Detecting-fraudulent-bank-notes-using-ML/blob/main/BankNote_Authentication.csv) has information on statistical measures assigned to each bank note. It has 1372  rows (bank notes) and 5 columns (atribites-statistical measures).

Source: https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data

UCI: http://archive.ics.uci.edu/ml/datasets/banknote+authentication

## Data preprocessing

No **`Data preprocessing`** tasks were performed, because the data are scarce and the target to be predicted `Class` is balanced.
Univariate and bivariate analyses were carried out to determine the frequency distributions of each attribute and the correlation between them.

They can be viewed at the following link:

[notebook](https://github.com/fedeandresg/Detecting-fraudulent-bank-notes-using-ML/blob/main/bank_notes.ipynb)

## Classification models - Machine Learning

The following classification models were used for the project:

- Logistic regression
- Support Vector Machine
- Support Vector Machine (rbf kernel)
- Randon Forest Classifier
- Kneighbors Classifier
- Multilayer Perceptron (neural network)

All models presented great results in terms of accuracy. The confusion matrices confirm the fact that they all predict the label 'Class' very well.

They can be viewed at the following link:

[notebook](https://github.com/fedeandresg/Detecting-fraudulent-bank-notes-using-ML/blob/main/bank_notes.ipynb)

