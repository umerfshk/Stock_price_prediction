# AMD Stock Price Prediction Using Machine Learning

## Table of Contents
1. [Introduction](#introduction)
2. [Company Selection & Background](#company-selection--background)
   - [Advanced Micro Devices Inc. (AMD)](#advanced-micro-devices-inc-amd)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Data Collection](#data-collection)
   - [Feature Generation](#feature-generation)
   - [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Machine Learning Classification Methods and Their Evaluation](#machine-learning-classification-methods-and-their-evaluation)
   - [Cross-validation for Model Evaluation](#cross-validation-for-model-evaluation)
   - [Evaluation of Methods](#evaluation-of-methods)
   - [Confusion Matrix and ROC Curve](#confusion-matrix-and-roc-curve)
   - [Feature Importance](#feature-importance)
5. [Market and Strategy Returns](#market-and-strategy-returns)
   - [EDA of Market and Strategy Returns](#eda-of-market-and-strategy-returns)
   - [Cumulative Returns Analysis](#cumulative-returns-analysis)
6. [Predictive Capabilities of Machine Learning](#predictive-capabilities-of-machine-learning)
7. [References](#references)

## Introduction
This project aims to analyze the stock data of Advanced Micro Devices Inc. (AMD), process it, and build a trading strategy using machine learning methods to predict future stock prices. We will evaluate the accuracy of these models, analyze feature importance, and explore the relationship between various dataset features.

## Company Selection & Background

### Advanced Micro Devices Inc. (AMD)
AMD is a leading global company in the microprocessor industry, focused on high performance in the data center and PC markets. Under the leadership of CEO Lisa Su, AMD has made significant advancements, especially in competing with Nvidia. This project examines AMD's stock performance and explores the effectiveness of machine learning in predicting stock values.

## Exploratory Data Analysis (EDA)

### Data Collection
Historical data for AMD will be obtained from Yahoo Finance, covering the period from January 1, 2014, to December 31, 2023. The data will be saved in a CSV file for efficient processing.

### Feature Generation
We will compute various technical indicators, including:
- **Simple Moving Averages**: 10-day, 30-day, and 60-day.
- **Volatility**: 5-day rolling standard deviation.
- **Price Rise Indicator**: A binary column indicating if the next day’s close price is higher.

### Exploratory Data Analysis
Initial EDA will involve summary statistics, correlation matrices, and distribution histograms to analyze the relationships and characteristics of the dataset features.

## Machine Learning Classification Methods and Their Evaluation
We will employ three machine learning models to evaluate our trading strategy, including:
- ExtraTreeClassifier
- K-nearest Neighbors (KNN)
- Naïve Bayes

### Cross-validation for Model Evaluation
Cross-validation techniques will be used to assess the models, ensuring robust evaluation of their performance across different data subsets.

### Evaluation of Methods
The performance of the models will be evaluated using classification reports, confusion matrices, and ROC curves to identify strengths and weaknesses in their predictive capabilities.

### Confusion Matrix and ROC Curve
These metrics will provide insights into the true positive and false positive rates of our models, highlighting areas for improvement.

### Feature Importance
We will analyze which features are most influential in the models' predictions to better understand the underlying factors affecting AMD's stock price.

## Market and Strategy Returns

### EDA of Market and Strategy Returns
We will examine the market and strategy returns through histograms and correlation heatmaps to evaluate the relationship and performance of our trading strategy.

### Cumulative Returns Analysis
A comparative analysis of cumulative market and strategy returns will reveal the effectiveness of the proposed trading strategy against market performance.

## Predictive Capabilities of Machine Learning
Despite the implementation of machine learning algorithms, the results indicate that these models currently do not effectively predict stock price fluctuations for AMD. Performance metrics suggest a need for further refinement in feature selection and data preparation.

