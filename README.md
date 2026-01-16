# FUTURE_ML_02

CUSTOMER CHURN PREDICTION SYSTEM
Machine Learning Task 2 – Future Interns

PROJECT OVERVIEW
Customer churn refers to the phenomenon where customers stop using a company’s product or service. In highly competitive industries such as telecommunications, banking, and Software-as-a-Service (SaaS), customer retention is a critical business objective. Studies show that acquiring a new customer costs significantly more than retaining an existing one.

This project focuses on building an end-to-end Machine Learning–based Churn Prediction System that helps businesses proactively identify customers who are likely to churn. By analyzing historical customer data, predicting churn probability, and visualizing insights through a Power BI dashboard, the system enables data-driven decision-making and targeted customer retention strategies.

The project combines data science, machine learning, and business analytics, making it suitable for real-world enterprise applications.

OBJECTIVES
The primary objectives of this project are:
• To analyze customer behavior patterns using historical data
• To clean and preprocess raw customer datasets for modeling
• To build and compare multiple classification models for churn prediction
• To evaluate models using appropriate performance metrics
• To identify high-risk customers based on churn probability
• To present actionable insights using dashboards and reports suitable for business stakeholders

DATASET
Dataset Used: Telco Customer Churn Dataset (Kaggle)

The dataset contains customer-level information collected from a telecom service provider. It includes demographic details, service usage patterns, billing information, and contract-related attributes.

Key Features:
• Customer demographics such as gender and senior citizen status
• Service usage details including internet and phone services
• Contract type (Month-to-month, One year, Two year)
• Payment method and billing preferences
• Monthly charges and total charges

Target Variable:
Churn
• 1 – Customer has churned
• 0 – Customer has not churned

TOOLS AND TECHNOLOGIES
The following tools and technologies were used throughout the project:

• Python for data analysis and modeling
• Pandas and NumPy for data manipulation
• Scikit-learn for preprocessing, model training, and evaluation
• XGBoost for advanced gradient boosting classification
• Matplotlib for visualizations during exploratory analysis
• Google Colab as the development environment
• Power BI for interactive dashboard creation
• GitHub for version control and project documentation

PROJECT WORKFLOW

DATA PREPROCESSING
• Removed or handled missing and inconsistent values
• Converted categorical features into numerical format using encoding techniques
• Transformed the churn variable into a binary target
• Engineered additional features to improve model performance
• Scaled numerical features where required

MODEL DEVELOPMENT
Multiple classification models were trained and evaluated to identify the best-performing algorithm:

• Logistic Regression – Used as a baseline interpretable model
• Random Forest Classifier – Used to capture non-linear relationships
• XGBoost Classifier – Used for high-performance gradient boosting

Best Performing Model: XGBoost
The XGBoost model was selected due to its superior performance in terms of ROC-AUC score and recall, making it effective for identifying churn-prone customers.

MODEL EVALUATION
The models were evaluated using the following metrics:

• Accuracy – Overall correctness of predictions
• Precision – Ability to correctly identify churned customers
• Recall – Ability to capture actual churn cases
• F1-score – Balance between precision and recall
• ROC-AUC score – Overall classification performance
• Confusion Matrix – Breakdown of true vs predicted outcomes

CHURN PROBABILITY AND RISK SEGMENTATION
• Generated churn probability scores for each customer
• Categorized customers into risk segments:
– Low Risk
– Medium Risk
– High Risk

This segmentation enables businesses to prioritize retention strategies for customers most likely to churn.

POWER BI DASHBOARD
A professional Power BI dashboard was created to communicate insights effectively to business users. The dashboard includes:

• Total number of customers
• Total churned customers
• Overall churn rate
• Customer churn distribution (churned vs non-churned)
• Churn analysis by contract type
• Risk-level segmentation of customers
• Monthly charges vs churn relationship
• Interactive filters for contract type, payment method, and risk level

KEY INSIGHTS
• Customers on month-to-month contracts show significantly higher churn rates
• Higher monthly charges are strongly correlated with increased churn probability
• Customers with shorter tenure are more likely to discontinue the service
• Certain payment methods are associated with higher churn behavior
• High-risk customers contribute disproportionately to overall churn

BUSINESS RECOMMENDATIONS
Based on the analysis and model results, the following recommendations are proposed:

• Encourage customers to shift from month-to-month contracts to long-term plans
• Design targeted retention campaigns for high-risk customers
• Offer discounts, loyalty rewards, or bundled services to high-billing customers
• Monitor churn probability regularly to enable proactive intervention
• Use churn insights to improve customer experience and service quality

PROJECT STRUCTURE
data – churn_results.csv (model predictions and churn probabilities)
notebook – churn_prediction.ipynb (data preprocessing and modeling)
dashboard – churn_dashboard.pbix (Power BI dashboard)
report – Churn_Prediction_System_Report.pdf (project documentation)
README – project overview and instructions

RESULTS
• Successfully built a reliable churn prediction model
• Identified key factors driving customer churn
• Delivered actionable business insights through dashboards
• Developed a production-ready analytical solution suitable for real-world use
