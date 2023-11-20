# Module 12 Report Template

## Overview of the Analysis

In this analysis, the objective was to develop machine learning models for predicting loan statuses based on financial data. The dataset contained various financial attributes as features, and the target variable was the loan status, aiming to predict whether a loan was healthy or high-risk.

### Data Overview:
* Purpose: Predicting loan statuses based on financial data.
* Financial Information: Attributes related to loans, potentially including credit scores, income, loan amount, etc.
* Target Variable: Loan Status (Healthy or High-risk).
* Variable Insights: value_counts() showed the distribution of healthy and high-risk loans.

### Machine Learning Process:
* Data Preprocessing: Splitting data, handling missing values, separating features and labels.
* Model Training: Utilized Logistic Regression models on original and resampled data.
* Evaluation Metrics: Balanced accuracy score, precision, and recall used to assess model performance.
* Resampling Techniques: Employed RandomOverSampler from imbalanced-learn to handle class imbalance.

## Results

* Machine Learning Model 1:
  * Balanced Accuracy Score: 95.20%
  * Precision & Recall: 
    * Class 0 (Healthy Loans):
      * Precision: 100%
      * Recall: 99%
    * Class 1 (High-risk Loans):
      * Precision: 85%
      * Recall: 91%



* Machine Learning Model 2:
  * Balanced Accuracy Score: 99.37%
  * Precision & Recall:
    * Class 0 (Healthy Loans):
      * Precision: 100%
      * Recall: 99%
    * Class 1 (High-risk Loans):
      * Precision: 84%
      * Recall: 99%

## Summary

Based on the results, both models demonstrate strong performance in predicting healthy (class 0) loans with high precision and recall. However, when considering the prediction of high-risk (class 1) loans:

* Model 2 outperforms Model 1 in terms of balanced accuracy score and precision for high-risk loans (class 1), achieving a higher overall balanced accuracy score and slightly higher recall for class 1.
  
### Importance of Performance in Solving the Problem:
* Balanced Importance: If equal importance is given to both classes, Model 2's higher balanced accuracy score and comparable precision for class 1 make it a more suitable choice.
* Priority on High-Risk Loans: If correctly identifying high-risk loans is a priority, Model 2's slightly higher recall for class 1 loans may be beneficial.

### Final Conclusion:
Considering the higher balanced accuracy score and comparable performance in predicting high-risk loans, Model 2 appears to perform better overall. Hence, for a balanced approach or when focusing on correctly identifying high-risk loans, Model 2 is recommended.






