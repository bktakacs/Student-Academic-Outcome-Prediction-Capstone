# Student Academic Outcome Prediction

Springboard DSC Capstone 2 Project

_Author:_ Ben Takacs

## Project Overview
In days most recent, I strode into a kingdom of student data—grades, demographic lore, and engagement metrics. My noble charge: to wield algorithms and foresee each student’s academic destiny. Using preprocessing, feature crafting, and models ranging from logistic regression to XGBoost, this Capstone stands as testament to predictive might and interpretability.

## Data & Methodology
- Raw features: demographics (age, gender), test scores, attendance, engagement logs.
- Engineered features: rolling averages, flag indicators for missingness, zip-code socioeconomic buckets.
- Models assessed:
	- Logistic Regression with L₂ regularization
 	- Random Forest
 	- XGBoost
	- LGBM
- Evaluation: stratified cross-validation, ROC‑AUC, confusion matrix, calibration curves, SHAP-value interpretation

## Key Results
- Best model: LGBM with Bayesian optimized hyperparameters
  - accuracy score of 90.9
  - top features: admission grade, curricular units, previous qualification, and age at enrollment

 ## Future Improvements
 - Model again without curricular units (or only using 1st semester grades)
 - Inlcude cohort-level anaylsis
