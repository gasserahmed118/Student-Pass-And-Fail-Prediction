# Student Pass/Fail Prediction

## Overview
This project predicts whether a student will **pass or fail** based on various academic and personal features using **Decision Tree** and **Random Forest** classifiers. It demonstrates data preprocessing, model training, hyperparameter tuning, and model evaluation with clear visualizations.  

The dataset used is [Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance).

---

## Objectives
- Explore and preprocess student data for machine learning.  
- Compare the performance of **Decision Tree** and **Random Forest** classifiers.  
- Optimize hyperparameters using **GridSearchCV** for better model accuracy.  
- Visualize results with **confusion matrices** and **decision trees**.  

---

## Project Structure

student-pass-fail-prediction/
│
├── data/
│ └── student-mat-pass-or-fail.csv # Input dataset
├── src/
│ └── main.py # Main Python script with models
├── notebooks/
│ └── EDA.ipynb # Optional exploratory data analysis
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions

## Output:
  1. Baseline Decision Tree accuracy
  2. Tuned Decision Tree accuracy and classification report
  3. Random Forest accuracy and classification report
  4. Confusion matrices for both models
  5. Visualization of the Decision Tree


## Models
  1. Decision Tree
     1. Trained with and without hyperparameter tuning using GridSearchCV.
     2. Visualizes the tree structure to understand feature importance.
    
  2. Random Forest
    1. Ensemble of Decision Trees to improve generalization and reduce overfitting.
    2. Provides higher accuracy and a robust alternative to a single Decision Tree.
