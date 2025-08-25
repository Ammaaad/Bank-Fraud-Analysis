###### 🏦 **Bank Fraud Detection Analysis**



📌 **Overview**

This project explores synthetic banking transactions to detect suspicious activity using EDA, statistics, and rule-based indicators (no ML models). The goal is to uncover fraud-like patterns and provide actionable business insights.



🎯 **Objectives**

• Clean \& preprocess transaction data

• Explore transaction trends \& anomalies

• Apply Chi-Square \& Pearson correlation

• Define rule-based fraud indicators (e.g., high login attempts, abnormal amounts, unusual device/location)

• Visualize suspicious behaviors with Python

• Deliver insights for fraud monitoring



📂 **Dataset**

Includes fields such as:

• Transaction ID

• Account ID

• Amount

• Date

• Type

• Location

• Device ID

• IP

• Merchant ID

• Channel

• Customer Age

• Occupation

• Duration

• Login Attempts

• Balance

• Previous Transaction Date



🛠️ **Tools**

• Python (Pandas, NumPy, SciPy)

• Matplotlib \& Seaborn (visualizations)

• Jupyter Notebook



📊 **Key Findings**

• Chi-Square: Transaction Type linked to Channel (p < 0.05)

• Pearson: Higher transaction amounts correlated with lower balances

• **Fraud Indicators:**

  • Multiple failed logins before a transaction

  • Spending >3× customer’s average

  • Same account from multiple devices/locations in 24 hrs

• **Visuals:**

  • Online channels had more fraud attempts

  • Night-time (12–3 AM) activity showed higher risk

