# Loan Default Prediction using Machine Learning

This project utilizes machine learning algorithms, including Random Forest, XGBoost, and Neural Networks, to predict the likelihood of loan defaults. By analyzing key features and building a risk-scoring system, the project provides actionable insights for financial institutions to optimize their lending strategies.

---

## **Project Overview**
- **Objective**: Predict loan defaults and develop a risk-scoring system to categorize borrowers by their likelihood of default.
- **Dataset**: Loan applicant data with 20,000 entries and 18 variables, including income, credit score, and loan amount.
- **Tools Used**: R, Random Forest, XGBoost, Neural Networks, SHAP, and ggplot2.

---

## **Repository Structure**
loan_default_prediction/ ├── data/ │ └── Loan_default_updated.csv # Dataset used for training and testing ├── scripts/ │ └── Loan_default_prediction.Rmd # R script for data preprocessing and modeling ├── docs/ │ ├── Loan_default_prediction.pdf # Detailed report of methodology and findings │ └── report.pdf # Supporting analysis document ├── README.md # Overview of the project

yaml
Copy code

---

## **Key Features**
1. **Exploratory Data Analysis (EDA)**:
   - Visualized default trends by factors like age, income, credit score, and loan purpose.
   - Identified key correlations (e.g., higher loan amounts linked to higher default risk).

2. **Machine Learning Models**:
   - Implemented Logistic Regression, Random Forest, SVM, XGBoost, and Neural Networks.
   - Achieved best performance with Random Forest:
     - Accuracy: 88.5%
     - F1 Score: 93.88%
     - AUC: 71.09%

3. **Risk Scoring System**:
   - Categorized borrowers into risk levels (Very Low, Low, Medium, High, Very High).
   - Provided actionable insights for loan approval and mitigation strategies.

---

## **Results**
- **Key Insights**:
  1. Borrower income, interest rates, and loan amount are the most significant predictors of default.
  2. Random Forest model outperformed others, balancing accuracy and interpretability.
  3. Risk scoring system validated its effectiveness in distinguishing low-risk and high-risk borrowers.

- **Feature Importance**:
  - Top predictors:
    - Income
    - Interest Rate
    - Loan Amount
    - Credit Score

---

## **Visualizations**
- Age distribution by default status.
- Loan amount by default status.
- Risk scores for high-risk vs. low-risk borrowers.
- Feature importance using SHAP and Random Forest.

---

## **Business Impact**
- **Improved Lending Decisions**: Focus on high-risk applicants with stricter policies.
- **Enhanced Profitability**: Reduced default rates improve financial stability and revenue.
- **Data-Driven Insights**: Enables strategic lending policies tailored to borrower profiles.

---

## **Contact**
For inquiries or suggestions, feel free to [contact me](mailto:your_email@example.com).