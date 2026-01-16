# FUTURE_ML_02

CUSTOMER CHURN PREDICTION SYSTEM

Machine Learning Task 2 | Future Interns

📌 Project Overview

The Customer Churn Prediction System is an end-to-end machine learning and business analytics project designed to help organizations proactively identify customers who are likely to discontinue a service. Customer churn is a major challenge in industries such as telecom, banking, and SaaS, where retaining customers is significantly more cost-effective than acquiring new ones.

This project leverages historical customer behavior data to build classification models that predict churn probability. The results are presented through an interactive Power BI dashboard, enabling business stakeholders to understand churn drivers, identify high-risk customers, and implement targeted retention strategies.

By combining machine learning, data analysis, and business intelligence, this solution demonstrates a practical, real-world application of predictive analytics.

🎯 Project Objectives

The primary objectives of this project are:

To analyze customer behavior and service usage patterns
To identify factors that contribute to customer churn
To build and evaluate machine learning classification models
To predict churn probability for individual customers
To segment customers based on churn risk levels
To visualize churn insights using an interactive Power BI dashboard
To generate actionable business recommendations for customer retention

📊 Dataset Description

Dataset Used: Telco Customer Churn Dataset (Kaggle)

The dataset contains customer-level information from a telecommunications service provider, covering demographics, subscription details, service usage, and billing information.

Key Columns:

CustomerID – Unique customer identifier
Gender – Customer gender
SeniorCitizen – Indicates whether the customer is a senior citizen
Tenure – Number of months the customer has stayed with the company
Contract – Contract type (Month-to-month, One year, Two year)
PaymentMethod – Mode of payment
MonthlyCharges – Monthly billing amount
TotalCharges – Total revenue generated from the customer
Churn – Target variable indicating customer churn (Yes/No)

The churn variable was converted into binary format for machine learning modeling.

🧠 Methodology

1️⃣ Data Cleaning & Preprocessing

Removed or handled missing and inconsistent values
Converted categorical variables into numerical format using encoding techniques
Transformed the churn target variable into binary values
Scaled numerical features where required
Prepared clean and model-ready data

2️⃣ Feature Engineering

Created meaningful input features from raw customer data
Analyzed contract type, payment method, and service usage impact
Engineered risk-related attributes to improve churn prediction
Prepared final feature set for classification models

3️⃣ Model Building

Trained and compared multiple classification models:

Logistic Regression – Baseline and interpretable model
Random Forest Classifier – Captures non-linear relationships
XGBoost Classifier – Advanced gradient boosting model

XGBoost was selected as the final model due to its superior performance in identifying churn-prone customers.

4️⃣ Model Evaluation

Evaluated models using industry-standard metrics:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Confusion Matrix

Special emphasis was placed on recall to ensure high-risk churn customers were correctly identified.

5️⃣ Churn Probability & Risk Segmentation

Generated churn probability scores for each customer
Segmented customers into risk categories:
Low Risk
Medium Risk
High Risk

This segmentation enables businesses to prioritize retention efforts efficiently.

6️⃣ Visualization & Dashboard Development

Developed an interactive Power BI dashboard to present churn insights
Integrated churn predictions and risk segmentation results
Enabled slicers for dynamic analysis by contract type, payment method, and risk level

🛠 Tools & Technologies Used

Python (Pandas, NumPy, Scikit-learn, XGBoost)
Google Colab (model development and experimentation)
Matplotlib (EDA and analysis visualizations)
Power BI Desktop (dashboard creation and reporting)
GitHub (version control and documentation)

📈 Key Features of the Dashboard

Total customers, churned customers, and churn rate KPI cards
Customer churn distribution (churned vs non-churned)
Contract type vs churn analysis
Risk-level segmentation visualization
Monthly charges vs churn behavior analysis
Interactive slicers for contract type, payment method, and risk level

📂 Project Structure

Customer-Churn-Prediction/
│
├── data/
│   └── churn_results.csv
│
├── notebook/
│   └── churn_prediction.ipynb
│
├── powerbi/
│   └── Churn_Dashboard.pbix
│
├── report/
│   └── Customer_Churn_Prediction_Report.pdf
│
├── README.md

▶️ How to Run the Project

1️⃣ Run the Churn Prediction Model

Open churn_prediction.ipynb in Google Colab
Upload the dataset
Run all cells sequentially
Ensure churn_results.csv is generated successfully

2️⃣ Build the Power BI Dashboard

Open Churn_Dashboard.pbix
Load churn_results.csv
Verify all visuals, KPIs, and slicers
Save the final dashboard

📌 Business Insights

Month-to-month contract customers exhibit the highest churn rates
Customers with higher monthly charges are more likely to churn
Short-tenure customers represent a high-risk segment
High-risk customers contribute significantly to overall churn
Targeted interventions can substantially reduce customer loss

✅ Results & Outcomes

Successfully built a high-performing churn prediction model
Identified key drivers influencing customer churn
Delivered a business-ready Power BI dashboard
Demonstrated real-world application of machine learning in customer analytics

📄 Submission Artifacts

✔ Python Notebook (Data preprocessing & model building)
✔ Power BI Dashboard (.pbix)
✔ Churn Prediction CSV Output
✔ Final PDF Project Report
✔ Complete GitHub Repository

🗣 Internship / Interview Explanation (Professional)

“I developed a customer churn prediction system using machine learning classification models. The solution predicts churn probability, segments customers based on risk levels, and visualizes insights through an interactive Power BI dashboard. This system helps businesses proactively retain customers and reduce revenue loss by enabling data-driven decision-making.”


Just tell me 💼🚀
able for real-world use
