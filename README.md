# MachineLearning_CS1675
This repository contains all files for my personal term project for CS 1675 Introduction to Machine Learning (fall 2021). The goal of this project was to train a combination of classification and regression models to predict the fraction of corroded surface per test, based on coating material inputs. This project was sponsored by PPG Industries. 

## Explanation of the Data
The dataset that was used to train and evaluate the models consists of three groups of variables: chemistry {x1,x2,x3,x4}, manufacturing {v1,v2,v3,v4,v5}, and machine {m}. The dataset also consists of a set of derived features {x5,w,z,t}. The 'output' variable is the proportion of corroded surface, with 'y' being the logit-transformed output. 

## Models Trained
- Linear 
- Elastic Net 
- Neural Network
- Random Forest
- Gradient Boosted Tree
- Support Vector Machine (SVM)
- Deep Neural Network (DNN)
- Multivariate Additive Regression Splines (MARS) 

## File Contents
- Data_Exploration.Rmd
- Bayesian_Linear_Models.Rmd 
- Binary Classification Accuracy.Rmd 
- Binary Classification ROC.Rmd 
- Bonus Tuning w Adaptive Resampling.Rmd 
- Interpretation and Optimization.Rmd 
- Linear Predictions.Rmd 
- Linear_Models.Rmd 
- Regression Models.Rmd Test_Set_Predictions.Rmd
