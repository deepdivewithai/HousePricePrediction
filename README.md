# Housing Price Prediction Project

This project aims to predict median house prices using machine learning techniques. The dataset used in this project contains various attributes related to housing properties, and we employ both traditional machine learning models and neural networks for regression.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Overview](#project-overview)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Neural Network Implementation](#neural-network-implementation)
- [Conclusion](#conclusion)

## Introduction

In this project, we seek to develop predictive models to estimate median house values based on a dataset containing various features related to housing properties. We employ data preprocessing, exploratory data analysis (EDA), traditional machine learning models, and a neural network to accomplish this task. The project provides valuable insights into the world of housing price prediction and serves as a practical example of data-driven modeling.

## Dataset

The dataset used in this project is sourced from a CSV file and includes attributes such as the number of rooms, bedrooms, population, households, geographical data (latitude and longitude), and more. The target variable is the median house value, which is crucial in real estate assessment.

## Project Overview

- **Data Preprocessing**: We ensure data quality by handling missing values, transforming numerical features using logarithmic functions, and one-hot encoding categorical data.

- **Exploratory Data Analysis (EDA)**: We visualize the data through histograms and correlation heatmaps to gain insights into its characteristics and relationships between features.

- **Modeling**: We split the dataset into training and testing sets, standardize numerical features, and train two primary models: a Linear Regression model and a Random Forest Regressor. Hyperparameter tuning is performed to optimize the Random Forest model.

- **Evaluation**: Model performance is assessed using standard regression metrics, including mean squared error (MSE) and mean absolute error (MAE). The Random Forest Regressor outperforms the Linear Regression model.

- **Neural Network Implementation**: In addition to traditional models, we explore neural network-based regression using Keras. We create a deep neural network with multiple hidden layers and employ early stopping to prevent overfitting. Training and validation loss are visualized, and the R-squared (R2) score is calculated to assess the neural network's predictive accuracy.

## Conclusion

This project provides valuable insights and tools for predicting housing prices and working on real estate valuation tasks using data-driven approaches. The Random Forest Regressor is identified as the best-performing model, while the neural network offers an alternative approach to regression tasks.

Feel free to explore the code and documentation in this repository to gain a deeper understanding of the project and adapt it for your own use cases.

For more details, please refer to the [Jupyter Notebook](Model.ipynb) where the project was developed.
