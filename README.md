#US Patients Heart Attack Prediction - Data Cleaning & EDA

#Overview

This repository contains data cleaning and exploratory data analysis (EDA) on a dataset of US patients, with the target variable being heart attack occurrence. After preprocessing the data, various machine learning models are applied to predict the likelihood of a heart attack.

#Features

Data Cleaning: Handling missing values, outliers, and inconsistencies

Exploratory Data Analysis (EDA): Visualizing key patterns and relationships in the data

Feature Engineering: Selecting and transforming relevant features

Modeling: Applying multiple machine learning classifiers

Evaluation: Comparing model performance using various metrics

Dataset

The dataset contains patient attributes such as:

*Age

*Gender

*Blood Pressure

8Cholesterol Levels

*Heart Rate

*Medical History

*Other relevant health indicators





#Machine Learning Models Applied

The following classifiers were used to predict heart attack occurrence:

*AdaBoostClassifier

*GradientBoostingClassifier

*RandomForestClassifier

*KNeighborsClassifier

#Project Structure

├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks for EDA & experiments
├── src/                  # Source code
│   ├── preprocess.py     # Data cleaning & preprocessing functions
│   ├── eda.py            # Exploratory data analysis scripts
│   ├── model.py          # ML model implementations
│   ├── train.py          # Training script
│   ├── evaluate.py       # Model evaluation
├── requirements.txt      # Dependencies
├── README.md             # Project documentation

#Results

After training the models, evaluation metrics such as accuracy, precision, recall, and confusion matrix are analyzed to determine the best-performing model.

