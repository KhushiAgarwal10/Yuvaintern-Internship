# Week 3 - Data Modelling

## Project Title

Crop Yield Prediction using Machine Learning

---

# Overview

This project focuses on developing a machine learning model to predict crop yield using an agribusiness dataset. The cleaned dataset obtained from Week 1 and analyzed during Week 2 was used for model development. The dataset contains agricultural factors such as rainfall, pesticide usage, temperature, crop type, geographical area, and crop yield.

Since the target variable (crop yield) is numerical, a regression-based machine learning approach was selected.

---

# Objectives

* Prepare data for machine learning modelling
* Split dataset into training and testing sets
* Train a regression model
* Generate crop yield predictions
* Evaluate model performance
* Visualize model results

---

# Dataset Used

Dataset Name:
cleaned_crop_dataset.csv

Target Variable:

* hg/ha_yield (Crop Yield)

Input Features:

* Area
* Item
* Year
* Average Rainfall
* Pesticides Usage
* Average Temperature

---

# Machine Learning Algorithm

## Random Forest Regressor

Random Forest Regressor was selected because:

* It performs well on structured datasets.
* It can capture non-linear relationships.
* It reduces overfitting compared to individual decision trees.
* It provides feature importance scores for interpretation.

---

# Data Modelling Process

### 1. Data Preparation

* Loaded cleaned dataset
* Converted categorical variables using One-Hot Encoding
* Defined input features and target variable

### 2. Train-Test Split

* Training Data: 80%
* Testing Data: 20%
* Random State: 42

### 3. Model Training

* Trained Random Forest Regressor
* Generated predictions on test data

### 4. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

# Visualizations Included

## 1. Actual vs Predicted Plot

Used to compare predicted crop yield values with actual crop yield values.

### Insight:

Predicted values closely follow actual values, indicating good model performance.

---

## 2. Residual Plot

Used to analyze prediction errors.

### Insight:

Residuals are distributed around zero, suggesting that the model does not exhibit significant bias.

---

## 3. Feature Importance Plot

Displays the most influential features used by the Random Forest model.

### Insight:

Agricultural factors such as rainfall, temperature, and pesticide usage contribute significantly to crop yield prediction.

---

# Technologies and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

# Files Included

* Week3_README.md
* model_building.ipynb
* cleaned_crop_dataset.csv

---

# Output

The model successfully predicts crop yield using agricultural and environmental factors. Evaluation metrics and visualizations demonstrate the effectiveness of the machine learning approach.

---

# Conclusion

The crop yield prediction model was successfully developed using Random Forest Regression. The model learned meaningful relationships between agricultural variables and crop yield. Visual evaluation and performance metrics indicate that the model can be used as a reliable baseline for crop yield forecasting and future agricultural analytics projects.

---

# Author

Name: Khushi Agarwal

Internship: Yuva Internship - Machine Learning Data Analyst Internship
