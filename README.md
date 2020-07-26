# Prediction of Employee Turnover: a machine learning approach
<img src="https://github.com/SAB-6/Employeesattritionprediction/blob/master/Images/Attrition.PNG"/>

## Table of Content
  * [Overview](#Overview)
  * [Files](#Files)
  * [Programming language](#Programming-language)
  * [Dependencies](#Dependencies)
  * [Summary](#Summary)
  * [Acknowledgments](#Acknowledgments)
  * [Associated post](#Associated-post)
  * [References](#References)
 
## Overview

A common problem in human resources analytics is devising a means to retain the high performing employees as losing them has a negative effect on the company performance as well as their growth. Apart from the lower productivity from a replacement, the newer employee needs to familiarise themselves with the company operations, the process involved in searching for a new employee, interviewing and training (both formal and informal) the newly employed person makes employees’ turnover undesirable. The cost of replacing an employee can vary based on the employee’s skill level; however, the cost is usually very high for a highly skilled professional in comparison to an entry-level job. This project presents insights on reasons behind emloyees turnover as well as predictive  models on  employee turnover. The model employed include: logistic regression, random forest and gradient boosting.

## Files

This repo contains the underlisted files:
1. Employee_Attrition_HR_Analytics.ipynb : Contains scripts on the the exploration analysis, testing 3 models and makes prediction
2. Employee_Attrition_HR_Analytics_Model.ipynb: presents a clean model that automate the process in the script above
3. Predicting Employees Attrition.pptx: Power point presentation
4. Classification_report.txt : classification report from the best model (i.e with the highest precision)

## Programming language
- Python

## Dependencies
- Markdown==3.1.1
- matplotlib==3.1.1
- pandas==0.25.1
- scikit-learn==0.21.3
- seaborn==0.9.0

## Summary
Employee turnover remains a key challenge in HR analytics. The cost of replacing a highly skilled professional in terms of searching for a replacement, interviewing, and training the replacement is higher than working around retaining them. Here a machine learning model using logistic regression, random forest classifier as well as gradient boosting were used to predict employees’ turnover. The top 5 predictive features derived from the model are:
1. Overtime
2. Stock option level
3. Total working years
4. Job satisfaction
5. Job involvement

Furthermore, the probabilities for each employee staying or leaving were presented and it is a key deliverable that can inform devising a retention scheme for the employees that are likely to turn over.

## Acknowledgments
- Thanks to <a href="https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset">Kaggle</a> for providing free access to the dataset

## Associated post
 For more information about the model outcomes <a href="https://medium.com/@shereef.bankole_13733/prediction-employee-turnover-a-machine-learning-approach-cdce7ad57890">check this medium story</a> while insights from the exploratory data analsis can be found <a href="https://medium.com/@shereef.bankole_13733/few-reasons-behind-employees-turnover-evidence-from-exploratory-data-analysis-3e058bacd9b8">here</a>

## References
1. John, S., 2002. Job-to-job turnover and job-to-non-employment movement. A case study investigation. Personnel Review, 31(6), pp.710–721.
2. Ongori, H. (2007), A review of the literature on employee turnover. African Journal of Business Management, 1(3), 49–54.
3. <a href="https://www.kdnuggets.com/2017/06/7-techniques-handle-imbalanced-data.html">Handling sampling imbalance</a>
4. <a href="https://imbalanced-learn.readthedocs.io/en/stable/over_sampling.html">Synthetic minority oversampling technique (smote)</a>
5. <a href="https://towardsdatascience.com/beyond-accuracy-precision-and-recall-3da06bea9f6c">Beyond accuracy, precision and recall</a>
