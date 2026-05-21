# Lab6

# Ecommerce Customers Linear Regression Project

## Overview
This project applies Linear Regression on the Ecommerce Customers dataset to predict the yearly amount spent by customers.

## Dataset Information
The dataset contains customer information such as:
- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent

## Steps Performed

### 1. Data Exploration
Performed:
- head()
- info()
- describe()

to understand the dataset structure and features.

### 2. Data Cleaning
Removed unnecessary columns:
- Email
- Address
- Avatar

### 3. Exploratory Data Analysis (EDA)
Used:
- Pairplot visualization
- Correlation heatmap

to analyze relationships between variables.

### 4. Data Preparation
- Defined features (X) and target variable (y)
- Split the dataset into training and testing sets

### 5. Model Training
Trained a Linear Regression model using scikit-learn.

### 6. Model Evaluation
Evaluated the model using:
- MAE = 7.22
- MSE = 79.81
- RMSE = 8.93

### 7. Results
The model achieved good prediction performance. Length of Membership and Time on App showed strong influence on yearly customer spending.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
