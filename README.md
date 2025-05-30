﻿# Task - 1 (Data Cleaning and Preprocessing)

## Objective -
Clean and Learn how to prepare raw data for Machine Learning using the Titanic dataset.

## Tools Used -
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## 🧪 Steps Performed -
1. Explored the dataset and checked for missing values
2. Filled missing values (Age, Embarked) and dropped Cabin
3. Encoded categorical features (Sex, Embarked)
4. Normalized numerical features (Age, Fare)
5. Visualized and removed outliers
6. Exported the cleaned dataset

## Project Structure

ml-task1-data-cleaning/  
├── data/  
│ ├── Titanic-Dataset.csv  
│ └── Titanic_Cleaned.csv  
├── images/  
│ └── boxplot_fare.png  
├── 01_data_cleaning.ipynb  
└── README.md  


---

## 1. Dataset Info

- Name: Titanic Dataset
- Source: [Kaggle - Titanic - Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Features used:
  - PassengerId
  - Survived
  - Name
  - Age
  - Sex
  - Pclass
  - Fare
  - Embarked

## 2. Data Cleaning Steps

- Removed missing values from 'Age' using median imputation.
- Converted categorical columns using LabelEncoding and OneHotEncoding.
- Detected and removed outliers using IQR method.
- Normalized numerical features using StandardScaler.

## 3. Visualizations

- Boxplot for Age & Fare
- Correlation heatmap
- Histogram of passenger classes

## 4. Results

- Final dataset shape: (891, 10)
- Outliers removed: 20 rows
- Ready for ML training phase ✅


# What I Learned -

- How to handle missing values in a dataset
- Encoding techniques for categorical variables
- Visualizing and removing outliers
- Feature scaling using StandardScaler


