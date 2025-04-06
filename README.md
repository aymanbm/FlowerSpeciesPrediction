# Flower Species Prediction
This project aims to classify flowers into their respective species using a range of classification algorithms. The analysis leverages advanced statistical and machine learning models to explore patterns in the dataset and accurately predict species labels.

## Objective
The main goal is to compare the performance of multiple classification models—Quadratic Discriminant Analysis (QDA), K-Nearest Neighbors (KNN), and Random Forest—in predicting flower species based on various measured attributes. Each model’s accuracy and robustness are evaluated to determine the most effective approach for this classification task.

## Dataset Overview
The dataset contains measurements for various flower species and includes the following features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Species (target variable)

## Data Preparation
Cleaned the dataset by handling missing or inconsistent values.

Standardized the numerical features to ensure fair comparison across models, especially for distance-based algorithms like KNN.

Handled outliers using the Interquartile Range (IQR) method, which improves model performance by removing extreme values.

Split the dataset into training and testing sets to evaluate generalization.

## Models Compared
Three classification algorithms were applied and evaluated:

Quadratic Discriminant Analysis (QDA): A probabilistic classifier assuming class-specific covariance matrices.

K-Nearest Neighbors (KNN): A non-parametric method based on proximity to labeled training examples.

Random Forest: An ensemble learning method using multiple decision trees and majority voting.

## Model Evaluation
Each model was assessed using:

Accuracy

Confusion Matrix

Cross-validation

Precision & Recall

F1-Score

## Installation & Setup

Ensure you have Python installed along with the required libraries.

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
