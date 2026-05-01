# Problem Statement
Predict student exam performance using academic, lifestyle, and socioeconomic factors.
Identify key drivers to enable early intervention and improve academic outcomes.

# Dataset Description
StudentPerformanceFactors dataset with features like study hours, attendance, sleep, and previous scores.
Target variable is **Exam_Score** with ~6600 student records.

# Steps Performed
Data preprocessing, EDA, feature engineering, and model training using train-test split.
Model evaluation using R², MAE, RMSE along with visualization and insights.

# Models Used
Linear, Ridge, and Lasso Regression for baseline and regularization.
Decision Tree and Random Forest for non-linear prediction and classification tasks.

# Results
Linear and Ridge Regression performed best with lower error (RMSE ≈ 2.18). 
Random Forest achieved strong performance in classification tasks (F1 ≈ 0.98).

# Limitations
Depends on dataset quality and may not generalize to all real-world scenarios.
Limited features and possible bias can affect prediction accuracy.

# Future Improvements
Use real-world datasets and include behavioral/psychological factors.
Implement advanced models like XGBoost, deep learning, and deploy as a web app.


