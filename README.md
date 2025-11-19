💳 Credit Card Fraud Detection

📊 Project Overview

A comprehensive machine learning project designed to detect fraudulent credit card transactions using advanced business analytics and predictive modeling techniques.

🗂️ Repository Structure

File	Description

credit_card_fraud_detection.ipynb	Complete EDA & Preprocessing
Data_Overview.pptx	Project Presentation
README.md	Project Documentation

🔗 Dataset Information

Source: Kaggle Credit Card Fraud Dataset : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
Processed Dataset you can also download : https://drive.google.com/file/d/1CZiBQf-M2I5D1luaom_rmwgt7c22o47E/view?usp=drive_link
Total Transactions: 284,807 (Original) → 55,551 (Processed)
Features: 31 Original + 4 Engineered
Class Distribution: Highly Imbalanced

📈 Class Distribution
Transaction Type	Count	Percentage
Normal	55,394	99.72%
Fraud	156	0.28%
🛠️ Technical Implementation
🔧 Data Processing Pipeline
Data Collection & Loading

Data Quality Assessment

Missing Value Treatment

Duplicate Removal

Feature Engineering

Standardization (StandardScaler)

Correlation Analysis

📊 Feature Engineering

Feature	Description
Amount_scaled	Standardized transaction amount
Time_scaled	Standardized time feature
Hour	Extracted hour from timestamp
Day	Extracted day from timestamp

📈 Key Insights

🔍 Top Fraud Correlations
Positive Correlation	Negative Correlation
V11: 0.235	V17: -0.478
V4: 0.211	V14: -0.426
V2: 0.170	V12: -0.331
⚠️ Data Challenges
Severe Class Imbalance (355:1 ratio)

Right-skewed Amount Distribution

Limited Time Window (13.1 hours)

🚀 Getting Started
📥 Installation & Setup
Download Dataset from Kaggle

Clone Repository

bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
Install Dependencies

bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
Run Analysis

bash
jupyter notebook credit_card_fraud_detection.ipynb
🛡️ Ethical Considerations
Privacy Protection: All features anonymized via PCA

Bias Mitigation: SMOTE/undersampling strategies planned

Ethical Use: Fraud prevention & customer protection focus

📋 Next Steps
Feature Selection based on correlation analysis

Address class imbalance (SMOTE/Undersampling)

Model Development (Logistic Regression, Random Forest, XGBoost)

Model Evaluation & Optimization

Deployment Strategy

👨‍💻 Author

Abdullahi Mohamed Jibril
Data Analytics Capstone Project
November 19, 2025

📄 License
This project is for educational purposes as part of academic coursework.
