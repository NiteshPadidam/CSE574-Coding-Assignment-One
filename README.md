# CSE574-Coding-Assignment-One
This README provides an overview of the code and process for performing Linear Regression using the closed-form solution and Logistic Regression using Gradient Descent.
## Table of Contents

1. [Introduction](#introduction)
2. [Linear Regression](#linear-regression)
3. [Logistic Regression](#logistic-regression)
4. [Requirements](#requirements)

## Introduction

Linear and Logistic Regressions are perfomed without using any in-built functions from libraries like sklearn

## Linear Regression 

Linear regression is the problem of finding a linear relationship between certain features of a given dataset. Closed-form solution method for Linear Regression is used to model data and resultant weight vectors are used for predicting the data.
These are  Explain the mathematical background and how it works.


## Logistic Regression 

logistic regression is a binary classification problem.In logistic regression, the target value discrete-valued (0,1) .So, the model of linear regression should be modified a little bit to deal with discrete-valued outputs. For this purpose, the logistic function(sigmoid function) can be applied to the model of the linear regression models. Weight vectors are founbd using Gradient Descent method and the learning rate is defined and the number of iterations are also defined.

### Code Structure

- dataset is imported
- data preprrocessing is performed using pandas and numpy
- modelling of data is performed using matrix operations for Linear Regression
- modelling of data is performed by creating a class of Logistic Regression

## Requirements

It is perfomed in python version. 
Following are the neccesary libraries 
- numpy 
- pandas
- matplotlib
- seaborn

