# credit_risk_classification

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate a machine learning model capable of predicting loan risk from financial data. Specifically, we sought to determine whether individual loans are likely to be healthy (`0`) or high-risk (`1`). The dataset included various financial indicators that could influence loan status, such as income, credit score, and debt level.

Throughout this process, we:
- Extracted the `loan_status` column as our target variable.
- Utilized remaining columns as features to predict the target.
- Split the data into training and testing sets.
- Applied logistic regression, a machine learning algorithm suitable for binary classification tasks.

The goal was to assess the logistic regression model's effectiveness in predicting both classes of the loan status, ensuring it could reliably identify both healthy and high-risk loans.

## Results

The logistic regression model's performance is summarized below:

* **Machine Learning Model 1: Logistic Regression**
    * **Accuracy**: The model achieved an overall accuracy of 99%, indicating a high level of correct predictions across both loan types.
    * **Precision for `0` (Healthy Loans)**: 1.00, meaning almost all loans predicted as healthy were truly healthy.
    * **Recall for `0` (Healthy Loans)**: 0.99, indicating that the model captured 99% of all actual healthy loans.
    * **Precision for `1` (High-Risk Loans)**: 0.85, reflecting that 85% of loans identified as high-risk were correctly classified.
    * **Recall for `1` (High-Risk Loans)**: 0.91, suggesting that the model identified 91% of all true high-risk loans.
    * **F1-Score for `0` (Healthy Loans)**: 1.00, combining precision and recall into a single metric.
    * **F1-Score for `1` (High-Risk Loans)**: 0.88, effectively balancing precision and recall for high-risk loan predictions.

## Summary

The logistic regression model demonstrated a robust capability in predicting both healthy and high-risk loans with high accuracy, precision, and recall. Given its outstanding performance metrics, particularly the high recall rate for high-risk loans, this model is recommended for deployment in predicting loan status. This capability is crucial, especially in financial contexts where identifying high-risk loans early can significantly mitigate potential losses. The model's strength in reliably detecting high-risk loans, as evidenced by the recall of 0.91, aligns with the business objective of minimizing financial risk. Therefore, the logistic regression model is not only effective but also appropriate for the specific needs of loan risk assessment.
