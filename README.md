🏦 Loan Default Prediction Project
This project focuses on building a machine learning model to predict whether a borrower will default on a loan based on financial and demographic data.

📁 Dataset Overview:
The dataset includes fields such as:

Gender, Marital Status, Education, Dependents

Applicant & Coapplicant Income

Loan Amount & Loan Term

Credit History

Property Area

Loan Status (target variable)

🧹 Preprocessing Steps:
Missing values handled with appropriate imputation strategies

Categorical features encoded using Label Encoding / One-Hot Encoding

Normalization of income and loan amount features

📊 Exploratory Data Analysis (EDA):
Visualized default rates by gender, credit history, and property area

Found Credit History to be the most impactful feature (defaults mostly happen when credit history is missing or poor)

Loan approval more likely for applicants with higher incomes and good credit

🧠 Models Used:
Logistic Regression

Decision Tree Classifier

Random Forest Classifier

📈 Model Performance:
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	~81%	0.78	0.83	0.80
Decision Tree	~75%	0.71	0.78	0.74
Random Forest	~84%	0.82	0.85	0.83

✅ Best Model: Random Forest, with ~84% accuracy and strong recall and F1-score.

🔧 Tech Stack:
Python (pandas, numpy, sklearn, seaborn, matplotlib)

Jupyter Notebook

Excel → CSV conversion for deployment

ZIP compression for file size optimization

🎯 Goal:
To support financial institutions in making informed lending decisions by automating risk assessment and reducing loan defaults.
