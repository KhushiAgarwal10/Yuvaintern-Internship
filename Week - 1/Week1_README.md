# Week 1 - Data Collection and Cleaning

## Project Title

Agribusiness Crop Yield Data Cleaning and Preprocessing

---

# Overview

This project focuses on data collection, cleaning, and preprocessing of an agribusiness dataset for machine learning analysis. The dataset selected is related to crop yield prediction and contains information such as rainfall, pesticide usage, temperature, crop production, and agricultural yield.

The main objective of this task is to improve the quality of the dataset by performing preprocessing techniques including:

* Handling missing values
* Checking duplicate records
* Outlier analysis
* Data normalization

The cleaned dataset can be further used for machine learning model development and agricultural data analysis.

---

# Dataset Used

Dataset Name:
yield_df.csv

Dataset Source:
Kaggle Crop Yield Prediction Dataset

Features Included:

* Area
* Item (Crop Type)
* Year
* Average Rainfall
* Pesticides Usage
* Average Temperature
* Crop Yield

---

# Technologies and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# Data Cleaning Steps Performed

1. Imported dataset using Pandas
2. Checked dataset structure and summary
3. Checked missing values using isnull().sum()
4. Checked duplicate rows using duplicated().sum()
5. Performed outlier analysis using boxplots
6. Applied normalization using MinMaxScaler
7. Saved cleaned dataset as CSV file

---

# Files Included

* data_cleaning.ipynb
* yield_df.csv
* cleaned_crop_dataset.csv
* requirements.txt

---

# Output

The final cleaned dataset is normalized and ready for machine learning analysis.

---



