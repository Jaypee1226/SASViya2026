# SAS Viya 2026 Kaggle Competition

This repository contains the source code, notebooks, and supporting files developed for the **SAS Viya Workbench for Learners 2026 Kaggle Competition**.

---

## Repository Contents

- **SAS_Viya2026.ipynb**  
  Primary notebook containing the complete data preparation, exploratory analysis, preprocessing, model benchmarking, and submission workflow.

- **SAS_Viya2026_Optimization.ipynb**  
  Optimization notebook dedicated to improving model performance through Gradient Boosting hyperparameter tuning and feature selection experiments.

- **submission.csv**  
  Final competition submission generated from the best-performing model.

- **gradient_boosting_results.csv**  
  Performance comparison of all Gradient Boosting hyperparameter experiments.

- **README.md**  
  Project documentation.

---

## Machine Learning Models Evaluated

The following regression models were evaluated during the experimentation phase:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- Decision Tree Regressor
- Forest Regressor
- Gradient Boosting Regressor

---

## Optimization Strategy

The optimization process included:

- Data quality assessment
- Missing value handling
- Feature preprocessing
- Feature profiling
- Gradient Boosting hyperparameter tuning
- Model comparison using validation RMSE

---

## Evaluation Metric

Model performance was evaluated using:

- **Root Mean Squared Error (RMSE)**
