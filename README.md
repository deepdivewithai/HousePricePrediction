# Housing Price Prediction Project

In this project, I set out to predict median house prices using various machine learning techniques. The dataset I used contains a wealth of information related to housing properties. Throughout this project, I explored traditional machine learning models as well as neural networks for regression tasks.

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

In this project, my main goal was to develop predictive models capable of estimating median house values based on a dataset comprising various features related to housing properties. I took a comprehensive approach, including data preprocessing, exploratory data analysis (EDA), traditional machine learning models, and even a neural network. This project provides a practical example of data-driven modeling in the realm of housing price prediction.

## Dataset

For this project, I utilized a dataset that I sourced from a CSV file. This dataset contains a wide range of attributes, including the number of rooms, bedrooms, population, households, geographical coordinates (latitude and longitude), and more. The target variable I aimed to predict is the median house value, which holds significant importance in real estate valuation.

## Project Overview

- **Data Preprocessing**: I ensured data quality by handling missing values, applying logarithmic transformations to specific numerical features, and one-hot encoding categorical data.

- **Exploratory Data Analysis (EDA)**: To better understand the data, I visualized it through histograms and correlation heatmaps. This helped me uncover valuable insights into the dataset's characteristics and relationships among its features.

- **Modeling**: I divided the dataset into training and testing sets, standardized numerical features using the StandardScaler, and proceeded to train two primary models: a Linear Regression model and a Random Forest Regressor. I also conducted hyperparameter tuning to optimize the Random Forest model's performance.

- **Evaluation**: I evaluated model performance using standard regression metrics, such as mean squared error (MSE) and mean absolute error (MAE). The Random Forest Regressor consistently outperformed the Linear Regression model.

- **Neural Network Implementation**: In addition to traditional models, I explored the use of neural networks for regression using Keras. I designed a deep neural network with multiple hidden layers and incorporated early stopping to mitigate overfitting. I visualized the training and validation loss and calculated the R-squared (R2) score to gauge the neural network's predictive accuracy.

## Conclusion

This project offers valuable insights and practical tools for those interested in predicting housing prices or working on real estate valuation tasks using data-driven methods. The Random Forest Regressor emerged as the superior model for this dataset, while the neural network provided an alternative approach to regression tasks.

I invite you to delve into the code and documentation within this repository to gain a deeper understanding of the project and adapt it to your own specific use cases.

For more detailed information, please refer to the [Jupyter Notebook](Model.ipynb) where I developed and documented the project.
