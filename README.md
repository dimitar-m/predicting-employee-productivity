# Who Hits the Target? Forecasting Employee Productivity with Decision Trees

## Overview
This project predicts whether garment industry employees meet daily productivity targets using the **Productivity Prediction of Garment Employees** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees).

## How to Run  
- Open the latest version of the project in **NBViewer**:  
  [View in NBViewer](https://nbviewer.org/github/dimitar-m/predicting-employee-productivity/blob/master/predicting_employee_productivity.ipynb)
  
## Goals
- Create a binary classification target for meeting productivity goals.
- Train and evaluate Decision Tree and Random Forest models.
- Compare interpretability and performance.
- Identify key factors influencing productivity.

## Methods & Techniques
- **Data Cleaning & Preprocessing**: Handled missing values, encoded categorical features.
- **Exploratory Data Analysis**: Distribution plots, outlier detection, and categorical breakdowns.
- **Modeling**:  
  - Decision Tree Classifier
  - Random Forest Classifier with hyperparameter tuning (`RandomizedSearchCV`)
- **Evaluation Metrics**: Accuracy on train/test sets, cross-validation scores.
- **Interpretation**: Decision tree visualization, feature importance analysis.

## Key Results
- Decision Tree achieved ~84.72% test accuracy.
- Tuned Random Forest achieved ~84.26% test accuracy.
- Feature importance highlighted workload, overtime, and department as key predictors.

## License
- This project is licensed under the MIT License.
