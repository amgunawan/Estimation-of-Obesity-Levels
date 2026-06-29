# Estimation of Obesity Levels Based on Eating Habits and Physical Condition

A machine learning classification project that predicts an individual's obesity level based on eating habits and physical condition using the **UCI Obesity Dataset**. This project follows the **CRISP-DM** methodology and compares the performance of **Decision Tree** and **Random Forest** classifiers.

## Overview

Obesity is a major public health concern that is influenced by lifestyle, eating habits, and physical activity. This project aims to build a classification model capable of predicting one of seven obesity levels from demographic and lifestyle attributes.

The project includes data preprocessing, exploratory data analysis, feature engineering, model development, evaluation, and comparison to identify the most effective classification algorithm.

## Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition)
- **Dataset:** Estimation of Obesity Levels Based On Eating Habits and Physical Condition
- **Records:** 2,111
- **Features:** 17
- **Target:** Obesity Level (7 Classes)

### Target Classes

- Insufficient Weight
- Normal Weight
- Overweight Level I
- Overweight Level II
- Obesity Type I
- Obesity Type II
- Obesity Type III

## Project Workflow

This project follows the **CRISP-DM** framework:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Exploratory Data Analysis (EDA)
5. Modeling
6. Model Evaluation

## Models

The following machine learning models were implemented and evaluated:

- Decision Tree
- Random Forest

## Results

The models were compared using standard classification metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score

Among the evaluated models, **Random Forest** achieved the best overall performance due to its higher predictive accuracy, better generalization, and greater robustness compared to a single Decision Tree.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding
- Model training and evaluation
- Performance comparison
- Visualization of results

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Structure

```
├── Kelompok 5_ALP Data Mining.ipynb
├── obesity-levels.csv
└── README.md
```
