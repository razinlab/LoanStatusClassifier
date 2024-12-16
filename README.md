# Complete Machine Learning Pipeline for Loan Eligibility Classification
## Project Overview
This project predicts loan eligibility based on numerical and categorical data. It demonstrates proficiency in exploratory data analysis, data preprocessing, machine learning modeling and evaluation.

Full project is located in main.ipynb, the cells are broken down by section in the cells folder.

## Features
- Exploratory Data Analysis (EDA): Understanding the dataset through visualizations and statistical analysis.
- Data Cleaning: Handling missing values, outliers, and feature scaling.
- Preprocessing and Feature Engineering: Creating pipelines for numerical and categorical data as input for models.
- Model Selection: Comparing multiple machine learning models (e.g., Logistic Regression, Gradient Boosting, XGBoost, etc.).
- Hyperparameter Tuning: Crossvalidating with different parameters to find optimal results.
- Model Evaluation: Assessing accuracy for each model used

## Tools Used
- Python
- Libraries:
  - numpy, pandas, matplotlib, seaborn
  - sklearn
  - xgboost, lightgbm, catboost
- Jupyter Notebook (in Colab)

## Results
Achieved ~88% accuracy with logistic and SGD classifiers. A boosted decision tree classifier performed the best being rougly ~5% more accurate than linear classifiers.

## Next Steps
Some possible next steps for a more comprehensive solution are:
- Code optimizations to eliminate redundancy
- Online learning
- Deeper per feature data aggregation and analysis 
