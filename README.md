🏦 Bank Fraud Detection Analysis
📌 Project Overview

This project analyzes banking transaction data to identify suspicious or potentially fraudulent activity.
The focus is Data Analyst–level work: exploring the data, deriving fraud indicators, applying statistical tests, and creating business insights.
No machine learning models were used — instead, I applied EDA, statistics, and business rules to detect fraud-like patterns.

🎯 Objectives

Clean and preprocess transaction data.

Explore trends and unusual behaviors in transactions.

Apply statistical tests (Chi-Square, Pearson) to understand variable relationships.

Define rule-based fraud indicators (e.g., high login attempts, unusual transaction amounts, device/location changes).

Visualize suspicious patterns using Python plots.

Deliver actionable business insights for fraud monitoring.

📂 Dataset

The dataset contains synthetic banking transaction records with the following columns:

TransactionID

AccountID

TransactionAmount

TransactionDate

TransactionType (ATM, Online, POS, Transfer, etc.)

Location

DeviceID

IP Address

MerchantID

Channel (Online / Offline)

CustomerAge

CustomerOccupation

TransactionDuration

LoginAttempts

AccountBalance

PreviousTransactionDate

🛠️ Tools & Libraries

Python

Pandas, NumPy (data cleaning, analysis)

Matplotlib, Seaborn (visualizations)

SciPy (Chi-Square, Pearson correlation)

Jupyter Notebook

📊 Key Analysis & Findings

Chi-Square Test: TransactionType was strongly related to Channel (p < 0.05).

Pearson Correlation: Higher TransactionAmount often correlated with lower AccountBalance.

Fraud Indicators (Rule-Based):

Multiple failed login attempts before a transaction.

Transaction amount > 3× customer’s average spend.

Same account accessing from multiple locations/devices within 24 hrs.

Visualization Highlights:

Fraud attempts were higher in online channels.

Night-time transactions (midnight–3 AM) showed more suspicious behavior.