# Predictive Modeling — Study Time vs Exam Score (Linear Regression)

## Overview  
This project applies machine learning to predict exam performance based on study time, demonstrating a fundamental supervised learning workflow using Linear Regression.

---

## Problem Statement  
Predicting academic performance helps identify how effort translates into results.  
This project focuses on modeling the relationship between study time and exam scores.

---

## Objective  
- Build a regression model to predict exam scores  
- Quantify the impact of study time on performance  

---

## Dataset  

- Synthetic dataset representing student study behavior  
- Variables:  
  - hours_studied — number of hours spent studying  
  - exam_score — corresponding exam result  

---

## Methodology  

### Data Preparation  
- Structured dataset using Pandas  
- Defined features (X) and target variable (y)  

### Model Development  
- Applied **Linear Regression** from Scikit-learn  
- Trained model to learn relationship between study time and exam score  

### Prediction & Visualization  
- Predicted exam score for 9 hours of study  
- Visualized data points and regression line using Matplotlib  

---

## Results  

- Predicted score for 9 study hours: **~92.5**  
- Model coefficient: **~5.42**  

---

## Key Insights  

- Strong positive relationship between study time and exam performance  
- Each additional hour of study increases predicted score by ~5.4 points  
- Linear Regression effectively captures simple patterns in data  

---

## Limitations  

- Synthetic dataset (not real-world data)  
- Small sample size  
- Assumes linear relationship between variables  
- Does not include other factors (sleep, stress, learning quality)  

---

## Future Improvements  

- Use real-world datasets  
- Add more features (sleep, focus, environment)  
- Apply advanced models (Polynomial Regression, Random Forest)  
- Evaluate model performance using metrics (RMSE, R²)  

---

## Tech Stack  

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## Project Value  

This project demonstrates the ability to:  
- Build and train a machine learning model  
- Interpret model outputs (coefficients, predictions)  
- Translate data into quantitative insights  

---

## Author  

Data Science & Machine Learning student focused on predictive modeling and real-world data applications
