# OVerview
The project presents a machine learning approach to predict employee attrition using logistic regression,
random forest and gradient boosting.
The project addresses the followings:
1. Exploratory data analysis
2. Model development, prediction and model evaluation
3. Retention strategies
4. Conclusion

It contains four files
1. Employee_Attrition_HR_Analytics.ipynb : Contains scripts on the the exploration analysis, testing 3 models and makes prediction
2. Employee_Attrition_HR_Analytics_Model.ipynb: presents a clean model that automate the process in the script above
3. Predicting Employees Attrition.pptx: Power point presentation
4. Classification_report.txt : classification report from the best model (i.e with the highest precision)

# Programming language
- Python

# Dependencies
- Markdown==3.1.1
- matplotlib==3.1.1
- pandas==0.25.1
- scikit-learn==0.21.3
- seaborn==0.9.0

# Summary
Employee turnover remains a key challenge in HR analytics. The cost of replacing a highly skilled professional in terms of searching for a replacement, interviewing, and training the replacement is higher than working around retaining them. Here a machine learning model using logistic regression, random forest classifier as well as gradient boosting were used to predict employees’ turnover. The top 5 predictive features derived from the model are:
1. Overtime
2. Stock option level
3. Total working years
4. Job satisfaction
5. Job involvement
Furthermore, the probabilities for each employee staying or leaving were presented and it is a key deliverable that can inform devising a retention scheme for the employees that are likely to turn over.

# Acknowledgments
- Thanks to <a href="https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset">Kaggle</a> for providing free access to the dataset

# Associated post
 For more detail information about the model outcome <a href="https://medium.com/@shereef.bankole_13733/prediction-employee-turnover-a-machine-learning-approach-cdce7ad57890">check this medium story</a>

# References
1. John, S., 2002. Job-to-job turnover and job-to-non-employment movement. A case study investigation. Personnel Review, 31(6), pp.710–721.
2. Ongori, H. (2007), A review of the literature on employee turnover. African Journal of Business Management, 1(3), 49–54.
3. <a href="https://www.kdnuggets.com/2017/06/7-techniques-handle-imbalanced-data.html">Handling sampling imbalance</a>
4. <a href="https://imbalanced-learn.readthedocs.io/en/stable/over_sampling.html">Synthetic minority oversampling technique (smote)</a>
5. <a href="https://towardsdatascience.com/beyond-accuracy-precision-and-recall-3da06bea9f6c">Beyond accuracy, precision and recall></a>
