# Deeplearning and Diabetes

# Overview
This notebook creates four machine learning models to predict if a person has diabetes. The models used are: Logistic Regression, Random Forest, K Nearest Neighbors, and Deep Neural Network. This notebook also sets out to find which features are most important in determining if someone has diabetes. This was done by using the eli5 machine learning explainable library. This notebook is hosted on Kaggle and can be found here: https://www.kaggle.com/code/jarredpriester/can-deep-learning-predict-diabetes

# Purpose of this Project
The main purpose of this notebook was to create my first deep learning model. The secondary purpose was to get an insight into  what factors were most important for predicting diabetes.

# What Did I Learn
I learned how to implement a deep learning model for classification using the Keras library. The model consisted of four dense layers with the last layer using the sigmoid activation. I learned that glucose levels were the most important factor when predicting if someone has diabetes. Body Mass Index (BMI) was also an important factor.

# Dataset Used
The dataset was the PIMA Indian dataset. The dataset consists of females over the age of 21. There are 9 features including outcome, which is what we will be trying to predict.

# Files Used
diabetes.csv - dataset  
can-deep-learning-predict-diabetes.ipynb - python notebook
