# Titanic Survival Prediction

## Overview
Predicting passenger survival on the Titanic using Random Forest classification.
Kaggle competition score: 0.73684 | Cross-validation accuracy: 79.9%

## Approach
- Exploratory data analysis
- Feature engineering: extracted titles from names, created family size features
- Model: Random Forest with 100 estimators
- Evaluation: 5-fold cross validation

## Tech Stack
Python, Pandas, Scikit-learn, Seaborn, Matplotlib

## Key Insight
Extracting passenger titles from the Name column was the strongest engineered feature,
encoding age, gender and social status simultaneously.
