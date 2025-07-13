**📊 Mutual Funds Overview and Insights**

This project provides a comprehensive analysis of the top 30 mutual funds in India. Using data visualization, composite scoring, and interactive dashboards, it helps users understand the best-performing funds based on returns, risk levels, fund size, and expense ratios.


**🔍 Project Overview**

This project consists of:

✅ Data preprocessing and cleaning using Pandas

✅ Feature normalization and composite score calculation

✅ Mutual fund ranking based on key metrics

✅ Interactive dashboard built using Power BI

✅ Dataset sourced from Excel

**📁 Files Included**

mutual_funds_dataset.csv  -The dataset containing fund details such as returns, SIP, risk, expense ratio, etc.

Mutual_Fund_Analysis.ipynb-Jupyter Notebook (Colab) with full data analysis, cleaning, normalization, and ranking logic

mutual fund dashboard.png -Screenshot of the final Power BI dashboard

Top 25 Mutual Funds.xlsx  -Exported final ranked list of top 25 funds from analysis

**📈 Dashboard Highlights**
<img width="1692" height="803" alt="mutual fund dashboard" src="https://github.com/user-attachments/assets/85fc458f-85d7-4d37-9aac-8920b2b6e25c" />
Key Insights Visualized:

Total investment overview (Lump Sum, SIP)

Investment volume by fund type (Equity, Debt, Hybrid, etc.)

Average SIP amount

1-Year Returns by AMC (Fund House)

Top Fund Managers by AUM

Average Management Fees by Fund Strategy

Risk and Expense comparisons

**⚙️ Methodology**
1. Data Cleaning & Preparation
Removed nulls

Converted columns to proper data types

Handled '-' and 0 values appropriately

2. Normalization
Used MinMaxScaler to normalize financial metrics like:

Expense Ratio

1Y, 3Y, 5Y Returns

Sharpe, Sortino, Alpha, Beta

3. Composite Scoring
Weights were applied to normalized columns:

python
Copy
Edit
weights = {
    'expense_ratio': 0.2,
    'returns_1yr': 0.15,
    'returns_3yr': 0.15,
    'returns_5yr': 0.15,
    'sharpe': 0.1,
    'sortino': 0.1,
    'alpha': 0.1,
    'beta': 0.05
}
4. Fund Ranking
Final score used to rank top-performing mutual funds for investment decisions.

**🛠 Technologies Used**
Python (Pandas, Scikit-learn)

Jupyter Notebook / Google Colab

Power BI

Excel

**📌 Future Enhancements**
Automate data refresh using live APIs

Add historical performance tracking

Integrate risk-adjusted performance metrics

Deploy dashboard as a web app

**🧠 Learnings**
Practical understanding of mutual fund metrics

Building real-world scoring models

Creating investor-friendly dashboards

Applying data normalization and weight-based ranking

🙌 Feedback Welcome
Thank you for exploring my Mutual Fund Analysis project!
I’m always open to suggestions, improvements, or collaboration ideas.

📩 Feel free to connect with me on **LinkedIn**: [Amal K B](https://www.linkedin.com/in/amal-k-b-111b2b259/)  
📧 Or drop an email: 369amalkb@gmail.com


