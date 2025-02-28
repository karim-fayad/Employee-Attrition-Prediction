**#Employee Attrition Prediction – Google Advanced Data Analytics Capstone**

**Project Overview**

This project analyzes employee attrition at Salifort Motors, a fictional company from the Google Advanced Data Analytics Capstone. The goal is to predict whether an employee will leave the company based on factors such as job satisfaction, work hours, salary, and department. By understanding key attrition drivers, HR teams can develop strategies to improve employee retention.

**Business Problem**

High employee turnover can lead to significant costs for a company. The objective of this project is to:
✔ Identify the key factors influencing employee attrition
✔ Build a predictive model to determine if an employee is likely to leave
✔ Provide actionable insights to improve employee retention

**Dataset Description**

The dataset contains information on employee job performance, workload, and compensation.There are 14,999 rows, 10 columns.


**Approach & Methodology**

**1. Exploratory Data Analysis (EDA)**

• Descriptive Statistics

• Outliers detection	

• Correlated features with employee attrition

• Check missing values and duplicates

• Data Visualization

**2. Data Preprocessing**

• Encoded categorical variables 

• Removed Outliers

• Feature Selection for model prediction Train Test split

**3. Model Selection & Training**

Tested multiple models to predict employee attrition:
✅ Logistic Regression
✅ Random Forest 
✅ Decision tree

**4. Model Evaluation**
	•	Accuracy, Precision, Recall, and F1-score to assess model performance
	•	Feature Importance analysis to determine key factors driving attrition

**Key Findings & Insights**
	•	Employees with low satisfaction levels are more likely to leave
	•	Higher work hours & more projects contribute to higher attrition
	•	Low salary employees have the highest attrition rate
	•	There doesn't seem to be any department that differs significantly in its proportion of employees who left to those who stayed.

**Technologies Used**
	•	Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
	•	Machine Learning: Logistic Regression, Random Forest, Decision Tree
	•	Jupyter Notebook
	

**Summary of model results**

_Logistic Regression_

The logistic regression model achieved precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and accuracy of 83%, on the test set.

_Tree-based Machine Learning_

After conducting feature engineering, the decision tree model achieved AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2%, on the test set. The random forest modestly outperformed the decision tree model.

**Conclusion**

The models and the feature importances extracted from the models confirm that employees at the company are overworked.

To retain employees, the following recommendations could be presented to the stakeholders:

Cap the number of projects that employees can work on.
Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
Either reward employees for working longer hours, or don't require them to do so.
If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.
