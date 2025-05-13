# boston-housing-regression
Overview
This repository contains an exploration of regression techniques applied to the classic Boston Housing dataset. The project demonstrates the implementation and comparison of linear, multiple, and polynomial regression models to predict house prices.
Dataset
The Boston Housing dataset is a well-known dataset in machine learning that contains information about various features of houses in Boston and their prices. The dataset includes 506 samples with 13 feature variables such as:
- CRIM: Crime rate
- RM: Average number of rooms
- RAD: Index of accessibility to radial highways
- PTRATIO: Pupil-teacher ratio
- LSTAT: Percentage of lower status population
The target variable is MEDV: Median value of owner-occupied homes in $1000s.

boston-housing-regression/
├── 01_linear_regression/
│   └── linear_regression.ipynb
├── 02_multiple_regression/
│   └── multiple_regression.ipynb
├── 03_polynomial_regression/
│   └── polynomial_regression.ipynb
├── data/
│   └── boston.csv (oppure caricato da sklearn)
├── images/
│   └── plot_linear.png
│   └── plot_polynomial.png
├── README.md
└── requirements.txt

Techniques Implemented

Simple Linear Regression

Implementation of a basic linear model using a single feature
Visualization of the regression line
Model evaluation and interpretation


Multiple Linear Regression

Utilizing all relevant features of the dataset
Feature selection techniques
Analysis of feature importance


Polynomial Regression

Implementation of polynomial features
Model complexity vs. performance analysis
Overfitting detection and prevention

Requirements

Python 3.8+
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter


This project was created as part of my learning journey in data science and machine learning.
