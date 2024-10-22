# Biomechanics Pitch Velocity Prediction Model
## Overview
This repository contains a machine learning project aimed at predicting pitch velocities using biomechanical data. The project compares the performance of several regression models, including Gradient Boosting Regressor, Random Forest, SGD (Stochastic Gradient Descent) Regressor, and XGBoost.

## Introduction
Accurately predicting pitch velocities based on biomechanics data is crucial for optimizing player performance and preventing injuries. This project leverages advanced regression techniques to create predictive models using various biomechanical variables. The primary models compared in this project are:

Gradient Boosting Regressor
Random Forest Regressor
SGD Regressor
XGBoost Regressor

## Dataset
The dataset is from the Driveline Open Biomechanics Project. More specifically the pitching_poi_metrics.csv and pitching_metadata.csv


## Models
#### Gradient Boosting Regressor
Gradient Boosting Regressor builds an ensemble of weak prediction models, typically decision trees, and combines them to create a strong predictive model.

#### Random Forest Regressor
Random Forest Regressor is an ensemble method that fits multiple decision trees on various sub-samples of the dataset and averages the predictions to improve accuracy and control over-fitting.

#### SGD Regressor
SGD Regressor uses stochastic gradient descent to fit linear models for regression. It is efficient for large-scale data.

#### XGBoost Regressor
XGBoost Regressor is an optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.
