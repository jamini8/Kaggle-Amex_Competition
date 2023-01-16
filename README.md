# Kaggle-Amex_Competition

Competition link: https://www.kaggle.com/competitions/amex-default-prediction/overview

## Project details

Credit default prediction is central to managing risk in a consumer lending business. Credit default prediction allows lenders to optimize lending decisions, which leads to a better customer experience and sound business economics. Current models exist to help manage risk. But it's possible to create better models that can outperform those currently in use.

American Express is a globally integrated payments company. The largest payment card issuer in the world, they provide customers with access to products, insights, and experiences that enrich lives and build business success.

In this project, you’ll apply your machine learning skills to predict credit default. Specifically, you will leverage given dataset to build a machine learning model that challenges the current model in production. Training, validation, and testing datasets include time-series behavioral data and anonymized customer profile information. You're free to explore any technique to create the most powerful model, from creating features to using the data in a more organic way within a model.

## Dataset

The dataset contains aggregated profile features for each customer at each statement date. Features are anonymized and normalized, and fall into five general categories:

D_* = Delinquency variables
S_* = Spend variables
P_* = Payment variables
B_* = Balance variables
R_* = Risk variables
For example: ['B_30', 'B_38', 'D_114', 'D_116', 'D_117', 'D_120', 'D_126', 'D_63', 'D_64', 'D_66', 'D_68']

## Feature Engineering:
Imputation
Categorical Encoding
Scaling
Creating Features
Feature aggregation

## Machine learning models:
KNN
SVM
lightGBM classifier
XGB classifier
Neural Network



