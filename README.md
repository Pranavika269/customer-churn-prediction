Project Overview:
Customer churn prediction is a Machine Learning project that aims to identify customers who are likely to stop using a company’s services.
This helps businesses take preventive actions to improve customer retention.
🎯 Problem Statement
Many companies lose customers due to various reasons.
The goal of this project is to build a predictive model that can classify whether a customer will churn (leave) or not churn (stay).

🎯 Objectives
Analyze customer behavior
Identify factors affecting churn
Build a predictive ML model
Improve business decision-making

📊 Dataset Information
The dataset includes customer-related information such as:
Customer ID
Gender
Senior Citizen
Tenure
Monthly Charges
Total Charges
Contract Type
Payment Method
Internet Service
Churn (Target Variable)

🔍 Exploratory Data Analysis (EDA)
Performed the following:
Data cleaning and handling missing values
Distribution analysis of features
Churn distribution visualization
Correlation analysis using heatmap
📈 Key Insights:
Customers with high monthly charges are more likely to churn
Customers with long tenure are less likely to churn
Contract type plays a major role in churn

⚙️ Data Preprocessing
Removed null values
Encoded categorical features using:
Label Encoding / One-Hot Encoding
Feature scaling using StandardScaler
Split data into training and testing sets

🤖 Model Building
Algorithm Used: Random Forest Classifier
Train-Test Split: 80% training, 20% testing

📈 Model Evaluation
Model performance was evaluated using:
Accuracy Score
Confusion Matrix
Classification Report
