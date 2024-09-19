# Air Quality and Health Risk Prediction

## Project Overview

This project aims to predict health risk scores based on air quality data using various machine learning models. The dataset includes features related to air quality, weather conditions, and temporal information. The goal is to build and evaluate models to estimate health risks and provide insights into how different factors affect health outcomes.

## Project Description

This project involves the following tasks:
1. Data preprocessing and feature extraction.
2. Training and evaluating multiple machine learning models.
3. Analyzing model performance and interpreting results.

## Data

The data used in this project is stored in the `Air_and_Health_Impacts/Data/Air_Health.csv` file. The dataset includes information about air quality and health risk scores, along with other features.

## Models

- **Linear Regression**: A linear model for predicting health risk scores.
- **Decision Tree Regressor**: A decision tree-based model for regression tasks.
- **Random Forest Regressor**: An ensemble model using multiple decision trees.

## Evaluation

Model performance is evaluated using:
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
- **R-squared Score**: Represents the proportion of variance explained by the model.
- **Cross-Validation R-squared Scores**: Provides an average R-squared score across multiple folds of cross-validation.

Plots of actual vs. predicted values are generated to visualize model performance.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn


