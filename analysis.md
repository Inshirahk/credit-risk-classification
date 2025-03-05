# Module 12 Report Template

## Overview of the Analysis
The purpose of this analysis was to evaluate the performance of machine learning models in predicting the risk level of loans. Specifically, we aimed to determine whether a given loan was a 0 (healthy loan) or a 1 (high-risk loan) based on financial data.

The dataset included various financial attributes relevant to loan risk assessment. Our primary objective was to classify loans into the appropriate risk category with high precision and accuracy. The logistic regression model was chosen as the primary machine learning method due to its effectiveness in binary classification problems.

The analysis involved the following stages:

Data Preprocessing - Cleaning and preparing the dataset for training and testing.

Model Selection - Implementing logistic regression to classify loans.

Model Training - Training the logistic regression model on the dataset.

Model Evaluation - Measuring accuracy, precision, and recall to determine the model’s effectiveness.

## Results

Machine Learning Model: Logistic Regression

Accuracy: 94%

Precision:

0 (Healthy Loan): 100%

1 (High-Risk Loan): 87%

Recall: Not explicitly mentioned, but likely high given the overall accuracy.

## Summary

The logistic regression model demonstrated strong performance, achieving a high balanced accuracy of 94%. It predicted healthy, low-risk loans (0) with perfect precision (100%) but showed slightly lower precision (87%) for high-risk loans (1).

Recommendation

The logistic regression model performs well overall, making it a strong candidate for loan risk prediction.

If predicting high-risk loans (1) is a priority, improvements may be needed to enhance precision in that category.

Depending on the business context, additional models (such as decision trees or ensemble methods) could be explored to improve the precision of high-risk loan classification.

Overall, the logistic regression model is a reliable choice, but further refinement may be necessary for cases where high-risk loan prediction is critical.

