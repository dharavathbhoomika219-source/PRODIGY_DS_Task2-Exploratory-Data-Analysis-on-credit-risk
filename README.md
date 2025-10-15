# PRODIGY_DS_Task2-Exploratory-Data-Analysis-on-credit-risk
📋 Project Overview:
This project performs an Exploratory Data Analysis (EDA) on a Credit Risk dataset to uncover patterns, trends, and relationships that can help financial institutions assess the likelihood of loan default.
Credit risk analysis is a key part of lending decisions — understanding which customer profiles are more prone to default enables banks to minimize losses and make data-driven lending strategies.
🎯 Objective:
The goal of this project is to:
Understand the demographic, financial, and behavioral characteristics of borrowers.
Explore key variables affecting loan default risk.
Detect correlations between credit risk and customer attributes.
Prepare the dataset for future predictive modeling (e.g., credit scoring or risk classification).
🧩 Dataset Description:
The dataset contains information about customers’ personal, financial, and loan-related attributes.
| Feature           | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| customer_id       | Unique ID assigned to each customer                               |
| age               | Age of the applicant                                              |
| gender            | Gender of the applicant                                           |
| income            | Applicant’s income level                                          |
| employment_status | Employment type (salaried, self-employed, unemployed, etc.)       |
| loan_amount       | Total amount of loan applied                                      |
| loan_purpose      | Reason for applying for the loan                                  |
| credit_score      | Credit score rating                                               |
| loan_status       | Target variable indicating if the loan was paid back or defaulted |
⚙️ Technologies Used:
Python 3.x
Pandas – Data manipulation and wrangling
NumPy – Numerical computations
Matplotlib / Seaborn / Plotly – Data visualization and trend analysis
Jupyter Notebook – Interactive analysis environment
🧠 EDA Process:
The exploratory data analysis follows a structured workflow:
Data Loading and Inspection
Load dataset using Pandas
Check shape, data types, and missing values
Data Cleaning
Handle null or inconsistent values
Remove duplicates and outliers
Univariate Analysis
Distribution of numerical features (e.g., age, income, credit score)
Frequency of categorical features (e.g., gender, loan purpose)
Bivariate Analysis
Relationship between credit risk (loan_status) and key variables
Correlation heatmap for numeric features
Outlier Detection
Use boxplots to identify outliers in income and loan_amount
Feature Relationships & Insights
Compare income vs. loan default rate
Analyze default rate across credit score categories
Study the impact of employment status and loan purpose
📊 Key Insights:
Customers with low credit scores are significantly more likely to default.
Higher loan-to-income ratios correlate with increased risk.
Certain loan purposes (e.g., personal loans) have higher default rates than others.
Employment stability plays an important role in repayment capability.
📁 Repository Structure
├── data/
│   └── credit_risk_dataset.csv
├── notebooks/
│   └── EDA_Credit_Risk.ipynb
├── results/
│   ├── correlation_heatmap.png
│   ├── income_distribution.png
│   └── loan_status_by_credit_score.png
├── requirements.txt
└── README.md
💻 How to Run:
Clone this repository:
git clone https://github.com/your-username/Exploratory-Data-Analysis-on-credit-risk.git
cd Exploratory-Data-Analysis-on-credit-risk
Install dependencies:
pip install -r requirements.txt
Open the Jupyter notebook:
jupyter notebook notebooks/EDA_Credit_Risk.ipynb
Run all cells to reproduce the analysis and visualizations.
🧾 Results Summary:
The EDA highlights the importance of credit score, income, and loan amount in determining creditworthiness. These findings can guide feature engineering and model selection in future credit risk prediction models.
🧠 Next Steps:
Implement feature engineering for predictive modeling.
Build classification models (e.g., Logistic Regression, Decision Tree, Random Forest).
Evaluate models using metrics like ROC-AUC, Precision, and Recall.
🏆 Acknowledgments:
Dataset Source: [Kaggle / UCI Machine Learning Repository]
Libraries: Scikit-learn, Pandas, Matplotlib, Seaborn
Created by Dharavath Bhoomika
📩 dharavathbhoomika219@gmail.com
