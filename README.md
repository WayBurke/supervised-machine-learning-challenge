# Supervised Machine Learning - Predicting Credit Risk

## Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. The data will be used to created Machine Learning Models to classify the risk level of given loans. The Logistic Regression model and Random Forest Classifier will be compared to see which performs better.

## Overview
Machine Learning models, Logistic Regression model and Random Forest Classifier, were build to predict whether a loan will be approved or not. My educated guess is that the Random Forest Classifier will perform better than Logistic Regression classification, since the model fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.


## Conclusion
There is not a big difference in the performance between both models for the lending data provided. However, Random Forest Classifier had the higher Train Score of 0.9971 while Logistic Regression Model had a score of 0.9941, a difference of only 0.004.

Random Forest Classifier performed better than Logistic Regression classification because a random selection of features is selected each time which provides a greater ensemble to aggregate over producing a more accurate predictor - [Source](https://towardsdatascience.com/ensemble-methods-in-machine-learning-what-are-they-and-why-use-them-68ec3f9fef5f).

## Files and Folders included:
* Jupyter Notebook 
  * Credit Risk Evaluator.ipynb
  
* Resources folder
  * lending_data.csv