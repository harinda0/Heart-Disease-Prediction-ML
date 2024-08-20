# Heart Disease Prediction Using Machine Learning

## Overview
This repository contains a project aimed at predicting the presence of heart disease in patients using machine learning techniques. The UCI Heart Disease dataset is used to train and evaluate five different classifiers. The project includes the following components:

1. **Data Import and Preprocessing**:
   - Loading the dataset and handling missing values.
   - Scaling features to ensure consistent model performance.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzing the distribution of features such as age, cholesterol, and chest pain types.
   - Detecting and treating outliers and missing data.
   - Visualizing key relationships in the data.

3. **Model Implementation**:
   - Building and training five classifiers: Random Forest, SVM, Logistic Regression, KNN, and Decision Tree.
   - Using pipelines to automate preprocessing and model training.

4. **Model Evaluation**:
   - Testing the models on a separate test dataset.
   - Generating confusion matrices and classification reports.
   - Comparing models based on accuracy, precision, recall, F1-score, and ROC AUC score.

5. **Results Comparison**:
   - Identifying the best-performing model (Random Forest) based on ROC AUC score.
   - Discussing the strengths and weaknesses of each model.

## Key Features
- **Comprehensive Data Analysis**: Detailed exploration and visualization of the dataset.
- **Multiple Classifiers**: Implementation and comparison of five different machine learning models.
- **Performance Metrics**: Evaluation using various metrics, including ROC AUC score, to determine the best model.
- **Model Comparison**: Insightful discussion on the performance of each model.

## Files in this Repository
- `Final Project.ipynb`: Jupyter Notebook containing the entire analysis, from data preprocessing to model evaluation.
- `Heart Disease UCI.xlsx`: The dataset used in this project.

## Usage
This repository is a valuable resource for students and professionals interested in applying machine learning techniques to medical datasets. It provides practical examples of data preprocessing, model training, and evaluation, with a focus on improving model performance through careful data handling and metric analysis.

## Conclusion
The Random Forest classifier emerged as the best performer, with the highest ROC AUC score, indicating strong predictive capabilities. This project demonstrates the importance of model selection and evaluation in achieving accurate predictions in medical datasets.
