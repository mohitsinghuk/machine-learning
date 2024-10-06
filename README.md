# Machine-learning
## Overview
This project explores the application of multiple machine learning models to solve three distinct problems across different datasets: e-commerce customer behavior, diabetes prediction, and banking customer subscription behavior. The aim is to develop and evaluate models to identify significant factors influencing decisions and assess the impact of various data preprocessing techniques and model evaluation strategies on performance.

Datasets
Three datasets were used, each addressing a different problem:

Dataset 1: E-commerce Customer Behavior


Source: Online Shoppers Purchasing Intention Dataset

Objective: Predict customer purchase behavior based on engagement metrics, browsing patterns, and browser activities.

Problem Type: Classification

Dataset 2: Diabetes Prediction


Source: Diabetes Health Indicators Dataset

Objective: Classify patients based on health factors to predict the presence of diabetes.

Problem Type: Classification

Dataset 3: Bank Customer Subscription



Source: Bank Marketing Dataset

Objective: Predict whether a customer will subscribe to a fixed-term deposit based on demographic and financial factors.

Problem Type: Classification


## Project Objectives
Evaluate Cross-validation: Assess the impact of cross-validation on model performance compared to a simple train-test split.
Model Performance: Compare traditional machine learning models with neural symbolic learning to determine their effectiveness.
Hyperparameter Tuning: Explore the impact of hyperparameter tuning on model performance.


## Hypotheses

Experiment 1: Cross-validation does not significantly improve model performance compared to a train-test split.

Experiment 2: Neural symbolic learning does not perform better than traditional machine learning models with optimized hyperparameters.

Experiment 3: Hyperparameter tuning does not significantly improve model performance compared to default settings.


## Data Preparation

Cleaning and Preprocessing: Removal of duplicates, handling of null values, and addressing class imbalance.
Data Exploration: Visualizations like heatmaps, correlation matrices, and distribution plots to understand data characteristics.
Scaling and Encoding: Feature scaling and one-hot encoding for categorical data.
Dimensionality Reduction: Principal Component Analysis (PCA) to reduce noise and improve model performance.


## Models Implemented

Decision Tree: Used for its interpretability and effectiveness on small-to-medium datasets.

Multi-Layer Perceptron (MLP): Suitable for high-dimensional data with complex, non-linear relationships.

Support Vector Machine (SVM): Applied for its ability to handle multiple features effectively.

Neural Symbolic Learning (NSL): Combines neural networks and symbolic reasoning for logical pattern learning.

Q-Learning: Reinforcement learning approach evaluated on the datasets.


## Experiments and Results

Experiment 1: Cross-Validation Impact

Setup: Tested models on datasets using both cross-validation and a simple train-test split.

Outcome: Cross-validation showed improved and more reliable performance across most models, especially MLP and SVM.

Experiment 2: Model Performance Comparison

Setup: Compared traditional machine learning models (Decision Tree, MLP, SVM) with Neural Symbolic Learning.

Outcome: Neural Symbolic Learning outperformed other models, especially in handling complex patterns in data.

Experiment 3: Hyperparameter Tuning Effectiveness

Setup: Assessed the impact of hyperparameter tuning on model performance.

Outcome: Hyperparameter tuning improved model accuracy and balanced F1 scores, particularly for MLP and SVM.


## Results Summary

Neural Symbolic Learning (NSL): Achieved the highest accuracy and showed strong performance in capturing complex data patterns.

MLP: Demonstrated robust performance across datasets, particularly with oversampling and PCA.

SVM: Showed improved performance post-hyperparameter tuning but had challenges with imbalanced data.

Decision Tree: Faced issues with overfitting, especially on smaller datasets.

Q-Learning: Performed the least effectively, indicating limitations for certain classification tasks.


## Conclusion
The project highlighted the importance of cross-validation, data preprocessing, and hyperparameter tuning in machine learning. The results suggest that Neural Symbolic Learning is highly effective for complex data analysis, and MLP is robust for predictive tasks in high-dimensional data spaces.

 
## Future Work
Implement advanced preprocessing techniques like SMOTE for handling imbalanced datasets.

Explore comprehensive hyperparameter tuning strategies (e.g., grid search).

Further investigate Neural Symbolic Learning for improvements in complex data handling.

