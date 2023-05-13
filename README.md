# Water Potability Prediction

This project aims to predict the potability of water, i.e., whether the water is safe to drink or not, using Machine Learning (ML) and AutoML techniques. The main objective is to build a model that can help identify if the water is drinkable based on various features and data analysis.

## Introduction

Potable water, also known as drinking water, comes from surface and ground sources and is treated to levels that meet state and federal standards for consumption. Drinking raw, untreated water can cause gastrointestinal problems such as diarrhea, vomiting, or fever. Contaminated water and poor sanitation are linked to the transmission of diseases such as cholera, diarrhea, dysentery, hepatitis A, typhoid, and polio. Therefore, it is crucial to accurately determine the potability of water.

## Project Overview

The main aim of this project is to predict the potability of water using ML and AutoML algorithms. The project involves the following steps:

1. Data Analysis: Perform exploratory data analysis to gain insights into the dataset, identify any patterns or relationships, and understand the distribution of the features.

2. Data Preprocessing: Handle missing values, if any, by either imputing them or removing the corresponding rows/columns. Convert categorical variables into numerical representations using techniques like one-hot encoding or label encoding. Scale the numeric features if necessary.

3. Feature Engineering: Extract and create new features that might enhance the predictive power of the model. This step may involve transforming existing features, creating interaction terms, or engineering domain-specific features.

4. Model Building using ML Algorithms: Train ML models using various algorithms such as Logistic Regression, Random Forest, Support Vector Machines (SVM), or others. Split the dataset into training and testing sets, fit the models on the training data, and evaluate their performance on the testing data using appropriate evaluation metrics.

5. Model Building using AutoML: Leverage AutoML techniques to automate the process of training and selecting the best ML model. Tools like H2O provide a comprehensive framework for automatic model selection and hyperparameter tuning.

6. Model Evaluation: Assess the performance of the ML and AutoML models using evaluation metrics such as accuracy, precision, recall, F1-score, ROC AUC score, and confusion matrix. Compare the results of different models to identify the best-performing one.

7. Deployment and Usage: Once a satisfactory model is obtained, it can be deployed and used for making predictions on new, unseen data. Create a user-friendly interface or API to allow users to input the relevant features and get predictions on the potability of water.

## Results
The project has achieved the following results on the test dataset:

1. Logistic Regression:
     -  Accuracy: 62.26%
     -  ROC AUC score: 0.5027
2. Random Forest:
     - Accuracy: 68.26%
     - ROC AUC score: 0.6141
     - Support Vector Machines (SVM):
3. SVM
     - Accuracy: 68.26%
     - ROC AUC score: 0.6036

## AutoML (H2O):

### Best Model: StackedEnsemble_AllModels
Accuracy: N/A (Refer to the generated model performance summary)
Please note that these results are based on the specific dataset and algorithms used in this project. Results may vary with different datasets and algorithms.

## Conclusion
In conclusion, this project demonstrates the use of ML and AutoML techniques to predict the potability of water. By leveraging various algorithms and evaluation metrics, we can build models that can help identify if the water is safe

