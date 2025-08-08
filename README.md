# AI-ML-Task-4
## Classification with Logistic Regression

## Overview
This project involves building a binary classifier using Logistic Regression to predict whether a tumor is benign (0) or malignant (1) based on diagnostic features. The workflow includes data preprocessing, model training, evaluation using multiple metrics, ROC curve visualization, and threshold tuning.

## Dataset
The dataset used in this project is a Breast Cancer Diagnostic Dataset, containing numerical features extracted from images of breast masses along with a diagnosis label (B for benign, M for malignant).

## Tools and Libraries
Python
Pandas
NumPy
Matplotlib
Scikit-learn

## Steps
1. Import the Dataset
Load the dataset using Pandas.
Explore its structure and check for unnecessary columns.

2. Data Cleaning
Drop unused columns (id, Unnamed: 32).
Map diagnosis labels: B → 0 (benign), M → 1 (malignant).

3. Define Features and Target Variable
Features (X): All diagnostic numerical columns.
Target (y): Diagnosis column (0 or 1).

4. Train/Test Split
Split the dataset into 80% training and 20% testing using train_test_split.

5. Feature Standardization
Standardize features using StandardScaler to ensure all features are on the same scale.

6. Model Creation and Training
Create a Logistic Regression model (max_iter=10000).
Fit the model to the training data.

7. Model Evaluation
Confusion Matrix: Evaluate correct and incorrect predictions.
Classification Report: View precision, recall, f1-score, and accuracy.
ROC-AUC Score: Measure the classifier’s ability to separate classes.
ROC Curve: Plot the True Positive Rate vs. False Positive Rate with AUC value.

8. Threshold Tuning
Adjust the classification threshold from the default 0.5 to 0.3.
Compare confusion matrices before and after tuning.

9. Sigmoid Function Explanation
The sigmoid transforms the linear combination of features into a probability between 0 and 1. The decision threshold determines how these probabilities are converted into class labels.












Ask ChatGPT


