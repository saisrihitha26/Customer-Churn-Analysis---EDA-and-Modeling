# Customer-Churn-Analysis---EDA-and-Modeling
📌 Project Overview
This project focuses on identifying why customers leave (churn) and predicting which customers are likely to churn in the future using Exploratory Data Analysis (EDA) and multiple machine learning models.

Customer Churn is when customers stop using a product or service. Understanding churn helps businesses improve retention, optimize marketing strategies, and reduce revenue loss.

📊 Dataset Summary
Source: [Add dataset link here if available]

Target Variable: Exited (1 = churned, 0 = retained)

Key Features:

Demographic: Geography, Gender, Age, EstimatedSalary

Behavioral: Tenure, Balance, NumOfProducts, IsActiveMember, HasCrCard

Other: CreditScore, CustomerId, etc.

🧪 Tools & Libraries Used
Languages: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Techniques:

EDA for pattern discovery

Handling class imbalance with SMOTE

Feature scaling & encoding

Model evaluation with metrics like Accuracy, F1 Score, ROC AUC

📈 Machine Learning Models & Performance
Model	Accuracy	Recall	F1 Score	ROC AUC
Logistic Regression	70.37%	68.32%	0.473	0.764
Random Forest	86.20%	41.44%	0.539	0.852
K-Nearest Neighbors	75.23%	66.78%	0.512	0.777
Support Vector Machine	78.57%	66.27%	0.546	0.823
XGBoost	83.30%	60.96%	0.587	0.842
Gradient Boosting	81.70%	70.03%	0.598	0.860

✅ Insights & Takeaways
🔍 Gradient Boosting outperforms other models in balancing precision and recall and has the highest ROC AUC, making it the best choice for this churn prediction task.

🧠 XGBoost is a close second, offering strong overall performance.

⚠️ Random Forest has the highest accuracy but performs worse in identifying churned customers due to class imbalance.

📉 Logistic Regression performs the worst overall and is not suitable for this dataset.

🎯 Key Highlights
End-to-end machine learning pipeline: from cleaning and preprocessing to model selection and evaluation.

Emphasis on class imbalance handling using SMOTE and evaluation beyond accuracy (focus on F1 & ROC AUC).

Business-friendly insights derived from EDA to support customer retention strategies.

