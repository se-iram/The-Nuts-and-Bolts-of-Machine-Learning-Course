# Waze User Churn Prediction – Course Portfolio Project

This project is part of the **Google Advanced Data Analytics Certificate** (Course: The Nuts and Bolts of Machine Learning). The goal is to build a machine learning model to predict monthly user churn for Waze, identifying users who are likely to stop using the app.

## Project Summary

Waze is looking to improve user retention. This project focuses on creating a classification model that predicts whether a user will churn (leave) or be retained. By identifying at-risk users, Waze can take proactive steps to improve the user experience and engagement.

## Objectives

- Predict whether a user will churn or not (binary classification).
- Compare the performance of two tree-based models: **Random Forest** and **XGBoost**.
- Use recall and F1-score as key evaluation metrics, as identifying churners correctly is more critical than just overall accuracy.

## Models Used

- **Random Forest Classifier**
- **XGBoost Classifier**

Both models were optimized using `GridSearchCV` to tune hyperparameters and improve performance.

## Key Steps

- Imported required Python libraries
- Conducted feature engineering (including binary encoding for categorical features)
- Assigned a binary target variable
- Split the dataset into training, validation, and test sets
- Trained and evaluated both Random Forest and XGBoost models
- Compared models using recall, precision, F1 score, and accuracy
- Plotted a confusion matrix
- Identified and visualized the top 10 feature importances from the final model

## Evaluation

- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score
- **Model Comparison:** XGBoost and Random Forest were compared based on these metrics
- **Final Model:** XGBoost showed stronger recall performance and was selected as the final model
- **Confusion Matrix:** Used to evaluate prediction strengths and weaknesses

## Conclusion

This machine learning model helps Waze identify users who are likely to churn, allowing the business to implement strategies to retain them. The results will support the operations team in improving user retention and long-term growth.

## Files Included

- `notebook.ipynb` – Jupyter notebook with the full analysis and modeling process
- `executive_summary.pdf` – Business summary of the project, key insights, and impact
