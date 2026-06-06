# Student Placement Prediction & Data Analytics System

## Overview

This project analyzes factors that influence student placement outcomes using machine learning and data analytics techniques. The objective is to identify key academic and demographic factors that affect employability and build a predictive model capable of classifying whether a student will be placed after graduation.

The project was developed using the Campus Recruitment Analysis dataset from Kaggle and includes data preprocessing, exploratory data analysis (EDA), feature engineering, visualization, and machine learning model development.

## Features

* Exploratory Data Analysis (EDA)
* Outlier Detection and Removal using IQR
* Categorical Data Encoding using LabelEncoder
* Missing Value Handling
* Logistic Regression Classification Model
* Confusion Matrix Visualization
* ROC Curve and AUC Evaluation
* Statistical and Correlation Analysis

## Dataset

The dataset contains 215 student records with academic performance, educational background, work experience, specialization, placement status, and salary information.

**Target Variable**

* Placement Status (Placed / Not Placed)

**Key Features**

* Secondary School Percentage (SSC)
* Higher Secondary Percentage (HSC)
* Degree Percentage
* MBA Percentage
* Work Experience
* Gender
* Specialization
* Employability Test Score

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Data Preprocessing

The following preprocessing techniques were applied:

* Removed outliers using the Interquartile Range (IQR) method
* Encoded categorical variables using LabelEncoder
* Handled missing values
* Standardized feature values using StandardScaler
* Split data into training and testing sets (80/20)

## Machine Learning Model

A Logistic Regression classifier was developed to predict student placement outcomes.

### Evaluation Metrics

* Accuracy: 88%
* ROC-AUC Score: 0.95
* Confusion Matrix
* Precision, Recall, and F1-Score

## Key Findings

* Strong academic performance positively influences placement likelihood.
* Students with prior work experience generally showed better placement outcomes.
* MBA performance demonstrated only a weak relationship with salary levels.
* Earlier academic achievements (SSC and HSC scores) showed stronger predictive value for placement.

## Results

The Logistic Regression model achieved approximately **88% classification accuracy** and an **AUC score of 0.95**, demonstrating strong predictive capability in distinguishing between placed and non-placed students.

## Future Improvements

* Compare performance with Random Forest, XGBoost, and Support Vector Machines.
* Perform hyperparameter tuning to improve model performance.
* Develop an interactive dashboard for visualization and prediction.
* Deploy the model as a web application using Flask or Streamlit.

## Author

**Raul Jr. Jalin Manalo**
Bachelor of Computer Science (Hons)
Taylor's University
Specialization in Cybersecurity and Data Science
