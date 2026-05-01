# Problem Statement
Predict student exam performance using academic, lifestyle, and socioeconomic factors.
Help identify key influences to support early intervention and better academic decisions.

# Dataset Description
Uses the StudentPerformanceFactors dataset with features like study hours, attendance, sleep, and previous scores.
Target variable is Exam_Score for prediction.

# Steps Performed
Data preprocessing, EDA, feature engineering, and model training on split datasets.
Evaluation done using metrics like R², MAE, RMSE with cross-validation.

# Models Used
Linear, Ridge, and Lasso Regression for baseline and feature selection.
Decision Tree and Random Forest for capturing non-linear patterns and better accuracy.

# Results
Random Forest performed best with highest prediction accuracy.
Key factors like study hours, attendance, and prior scores strongly influenced performance. [(F1 ≈ 0.98), RMSE (~2.18)] 

# Limitations
Model depends on dataset quality and may not generalize to all student populations.
Limited real-world factors and possible bias in data can affect accuracy.

# Future Improvements
Use larger, real-world datasets and include more behavioral or psychological factors.
Apply advanced models like boosting or deep learning for improved performance.
