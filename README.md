# Student Performance Prediction — Linear Regression Model

## Overview

This project implements a simple linear regression model to analyze the relationship between study time and exam performance.

The objective is to demonstrate how machine learning can be used to identify patterns in data and make predictions based on those patterns.

---

## Problem Statement

Understanding the factors that influence academic performance is important in education.

This project aims to answer:

* Is there a relationship between hours studied and exam scores?
* Can we predict student performance based on study time?

---

## Data

A structured dataset was created with the following variables:

* `hours_studied`: number of hours a student studies
* `exam_score`: corresponding exam result

The dataset includes 8 observations representing increasing study time and performance.

---

## Methodology

### Data Preparation

* Data was organized into a Pandas DataFrame
* Features (`hours_studied`) and target (`exam_score`) were separated

---

### Model

A Linear Regression model was used to:

* model the relationship between study time and exam score
* estimate how much exam performance changes with additional study time

---

### Training

The model was trained on the full dataset to learn the linear relationship.

---

### Prediction

The model was used to predict the exam score for a student who studies 9 hours.

Predicted result:

```id="a1b2c3"
Predicted score for 9 hours: 92.5
```

---

### Visualization

A scatter plot was created to show:

* actual data points
* regression line representing the model

This helps visualize the relationship between study time and performance.

---

## Results

The model identified a positive linear relationship between study time and exam scores.

Model coefficient:

```id="d4e5f6"
5.4167
```


This means that, on average, each additional hour of study increases the exam score by approximately 5.42 points.

---

## Key Insights

* There is a clear positive correlation between study time and exam performance
* Linear regression is effective for modeling simple relationships
* Even small datasets can demonstrate fundamental machine learning concepts

---

## Limitations

* Small dataset size
* Data is synthetic and does not represent real-world variability
* Does not account for other factors (e.g., prior knowledge, sleep, environment)

---

## Future Improvements

* Use a larger, real-world dataset
* Include additional features (e.g., attendance, sleep, study methods)
* Evaluate model performance using metrics (R², MAE)
* Compare with more complex models

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## Repository Structure

```id="g7h8i9"
student-performance/
│
├── notebook.ipynb
├── README.md
```

---

## Author

Independent project demonstrating foundational skills in data analysis and machine learning.
