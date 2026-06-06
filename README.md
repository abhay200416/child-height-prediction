# 👶 Child Height Prediction

## Problem Statement
Predict a child's height based on parents' heights and child's gender.

## Dataset
- 7000 records
- Features: Father Height, Mother Height, Child Gender
- Target: Predicted Child Height (cm)

## Steps Followed
1. Exploratory Data Analysis
2. fill missing value
3. encod the data
4. 

## Results
- R² Score: 0.778
- RMSE: 4.0 cm  ← what does this mean in plain English?

## Libraries Used
pandas, numpy, scikit-learn, matplotlib

## What I Learned
 - How Linear Regression works internally — finding the best 
  weights (m) and bias (b) using Gradient Descent to minimize loss

- How to use StandardScaler to bring all features to the same 
  range so the model treats them equally

- How to do Feature Engineering — selecting only the most 
  relevant features using correlation analysis instead of 
  using everything blindly

- How to build a clean ML Pipeline using sklearn to chain 
  scaling and model training together

- That simpler models with fewer but stronger features can 
  outperform complex models with many weak features 
