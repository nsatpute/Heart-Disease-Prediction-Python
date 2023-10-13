# Heart-Disease-Prediction-Python
Data Source:
Kaggle - Personal Key Indicators of Heart Disease by CDC survey data in 2020 
319795 Observations
18 Features 

Target Variable - Heart Diseases

Step 1:
Check missing values 
Drop duplicates
Convert categorical variables to dummy variables 
YES/NO - 1,0
Convert categorical variables with multiple levels to dummy variables 
Convert numerical variables to categorical variable 

Step 2:
Use SMOTE to balance the data 

Models and Evaluation:
Performance Measures- 
1)The accuracy of logistic regression was 78%, whereas random forest was 82%. 
2)The precision of logistic regression was 77% whereas random forest was 80%.
3)The recall of logistic regression was 81% whereas random forest was 86%.
4)The F1 Score of logistic regression was 0.79 whereas random forest was 0.83.

Model Selection: 
Random Forest 
Higher Recall - lower False Negatives - Fewer patients with heart disease will be predicted as ‘NO’ 
Overall good performance in predicting patients with heart disease
