# Predicting Wine Quality

This project is the culmination of work done for the course MK842 - Machine Learning for Business Analytics at Boston University. The goal of this project was to apply various machine learning techniques to predict the quality of wine based on physicochemical properties.

## Team Members

- Willem Seethaler - Engineer & Code Author
- Shengyi Li - Assistant Code Author
- Prosper Nyandimu - Analyst
- German Santiago Eguiguren Rodriguez - Analyst

## Overview

The project involved exploring multiple regression models to establish a relationship between the wine's attributes and its quality. Models such as Linear Regression, Ridge Regression, Lasso Regression, Gradient Boosting, and Support Vector Regression were evaluated based on their Mean Squared Error (MSE) to predict the quality of wine effectively.

## Repository Structure

```plaintext

├── data
│   └── winequality.csv             # Dataset used for training and testing the models
├── models
│   ├── linear_regression        # Linear regression model
│   ├── ridge_regression         # Ridge regression model
│   ├── lasso_regression         # Lasso regression model
│   ├── gradient_boosting        # Gradient boosting model
│   └── svr                      # Support Vector Regression model
├── notebooks
│   └── Predicting_Wine_Quality.ipynb # Jupyter notebook with exploratory data analysis and model evaluation
├── README.md
