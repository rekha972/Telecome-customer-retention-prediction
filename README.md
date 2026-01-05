# Telecome-customer-retention-prediction
📌 PROJECT NAME


Telecom Customer Retention Prediction

🧩 Problem Statement

In the highly competitive telecom industry, customer churn directly impacts revenue and growth. This project aims to predict whether a customer is likely to discontinue telecom services by analyzing historical customer data. Early churn prediction helps companies design effective customer retention strategies.

📊 Data Description

The analysis is based on a telecom dataset consisting of 7,043 customer records and 21 attributes. These attributes capture customer demographics, service subscriptions, and billing information.

Numerical Attributes (4): tenure, MonthlyCharges, TotalCharges

Categorical Attributes (17): customer personal details, service usage, and payment-related features

Two columns were excluded during preprocessing:

CustomerID, as it is only an identifier

OnlineBackup, which was removed based on feature relevance analysis

🔍 Feature Overview

Independent Variables include numerical factors such as tenure and charges, along with categorical factors like gender, contract type, internet services, streaming services, billing preferences, and payment methods.

Dependent Variable:

Churn – indicates whether a customer has left the service (Yes/No)

📈 Exploratory Data Analysis (EDA)

EDA was carried out to uncover patterns and relationships influencing customer churn:

Comparison of churned and retained customers using bar charts

Distribution analysis of MonthlyCharges for male and female customers separately

Distribution analysis of TotalCharges by gender

Examination of customer tenure against churn behavior to understand loyalty trends

🧠 Key Findings

Customers with shorter tenure are more prone to churn

Spending behavior varies between male and female customers

The dataset shows class imbalance, with retained customers forming the majority

Numerical features exhibit right-skewed distributions

⚙️ Proposed Modeling Approach

To build an effective churn prediction model, the following steps are recommended:

Convert categorical features into numerical form using encoding techniques

Address class imbalance using SMOTE or weighted loss functions

Scale numerical variables to improve model stability

Train machine learning models such as Logistic Regression, Random Forest, and XGBoost

Evaluate model performance using Accuracy, Precision, Recall, and ROC-AUC

✅ Outcome

This project provides a complete analytical and predictive framework for identifying customers at risk of churn. The insights and models developed can support telecom companies in making proactive, data-driven decisions to enhance customer retention.

⭐ This narrative-style version is ideal for viva explanations, written reports, and interview discussions.

Done 👍
I’ve created another completely different style of the same project — a narrative / problem–solution style, which is very useful for:

🧑‍💼 Viva & interview explanation

📘 Project report (theory-oriented)

🗣️ Explaining your project confidently in simple English

Now you have multiple versions:

Professional GitHub style

Simple English paragraph style

Rewritten technical style

Narrative (problem–solution) style

If you want, I can still:

🔹 Make a very short 6–7 line version

🔹 Prepare a spoken 2-minute interview answer

🔹 Convert it into resume bullet points

🔹 Add Power BI / Tableau visualization explanation
