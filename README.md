🏦 Bank Loan Approval Prediction Model

📌 Project Overview
This project is a machine learning model that predicts whether a loan application will be approved or rejected based on applicant and loan-related information.
The dataset includes important financial and demographic features such as dependents, education, income, loan details, and asset value.
The main goal is to demonstrate end-to-end data science skills from data cleaning, EDA, preprocessing, feature engineering, modeling, evaluation, and deployment preparation.

🚀 Features of the Project:
✅ Data Cleaning & Preprocessing (handling missing values, encoding categorical variables, scaling numeric features)
✅ Exploratory Data Analysis (EDA) with visualizations to understand patterns and correlations
✅ Feature Engineering (created meaningful features to improve model performance)
✅ Implemented multiple ML models:

ALGORITHM USED:
Logistic Regression
Random Forest
XGBoost

✅ Model Evaluation using confusion matrix, classification report

✅ Model Serialization with Pickle for deployment

📊 Dataset Features
The dataset consists of the following features:

Feature	Description:
no_of_dependents	Number of dependents of the applicant
education	Applicant’s education status (Graduate/Not Graduate)
self_employed	Employment type (Yes/No)
income_annum	Annual income of the applicant
loan_amount	Requested loan amount
loan_term	Duration of the loan (in months)
Assets_value	Value of the applicant’s assets
loan_status	Target variable (Approved / Not Approved)

🛠️ Tech Stack
Python 3.9+
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, pickle
Jupyter Notebook for analysis & documentation

📊 Model Performance
Best Model: Logistic Regression (after weight balancing)
Accuracy: 56.4% (Even after hyperparameter tunning)
Precision & Recall

📈 Visualizations
Loan approval status
Applicant Income Distribution
Confusion matrix for model evaluation

🔮 Next Steps
Deploy model as a Flask / FastAPI API
Build a Streamlit dashboard for loan officers to test the model interactively
Improve model accuracy with advanced techniques (SMOTE, ensemble learning)

🙋‍♂️ Author
Olowomojuore Damilola Ibrahim
🌍 Data Analyst | Machine Learning Enthusiast | Environmental Engineer
