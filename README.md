# FinDataX

📌 Project Overview

This project explores a synthetic dataset from a fictional fintech company, FinDataX, with the goal of understanding the factors that may drive customer churn (service cancellation).
The dataset was generated with Mockaroo and includes information such as account activity, payments, app logins, and balances.

🎯 Objective

Identify which variables show a meaningful relationship with the churn indicator and visualize key patterns.

🗂️ Data

- Rows: ~5,000 customers
- Main columns:

  - late_payments – number of late payments
  - app_logins_last_month – logins in the last 30 days
  - avg_balance – average account balance
  - transactions_last_3m – number of transactions in the last 3 months
  - churn – 0 = active, 1 = canceled

The dataset is purely synthetic and was created only for learning and practice.

🧮 Analysis Performed

1. Exploratory Data Analysis (EDA)

- Descriptive statistics and distribution plots
- Histograms and boxplots for key variables

2. Correlation Check

- Computed a correlation matrix with pandas.corr()
- Visualized it using seaborn.heatmap

📊 Key Findings

- Late payments is the only variable with a noticeable positive correlation with churn.

  - “This table shows that late_payments is the only variable strongly correlated with service cancellation.”

- Other variables such as average balance, number of logins, and transactions showed only weak or negligible relationships.

🛠️ Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- Google Colab / Jupyter Notebook
