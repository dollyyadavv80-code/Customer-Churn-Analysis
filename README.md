# Customer Churn Analysis (Python + Power BI)

Customer Churn Analysis using Python + Power BI is a data analytics project focused on understanding customer churn patterns. Python and Pandas were used for data cleaning and EDA, while Power BI was used to create an interactive dashboard and generate meaningful business insights

# Dataset

IBM Telco Customer Churn sample dataset (7,043 customers, 33 columns) covering demographics, services, contract type, billing, tenure, charges, and churn reason.

# Workflow
- Data cleaning (Python): converted Total Charges to numeric, handled missing values, filled Churn Reason with "Not Churned" for retained customers
- EDA (Python): churn distribution, churn by contract, total charges vs churn, correlation heatmap, top churn reasons
- Dashboard (Power BI): built measures (Total Customers, Churn Customers, Churn Rate %), tenure groups, customer type, and the visuals

# Dashboard Overview
- KPIs: 7,043 total customers, 1,869 churned, 26.54% churn rate
- Visuals: churn by contract, churn rate by tenure group, monthly charges by customer type, monthly charges by Online Security and Online Backup, customer retention, average monthly charges by churn label
- Slicers: Gender, Customer Type

# Key Insights
- 26.54% of customers churned (1,869 of 7,043).
- Month-to-month contracts have far more churn than one-year and two-year contracts.
- Churn is highest in the first 12 months and drops as tenure increases.
- Churned customers pay a higher average monthly charge than retained customers.
- Top churn reasons: attitude of support staff and competitors offering higher download speeds.

# Recommendations
- Encourage month-to-month customers to move to longer contracts.
- Focus retention efforts on customers in their first 12 months.
- Improve support staff training and review internet speed plans against competitors.

 # Repository Structure
customer-churn-analysis/
```
customer-churn-analysis/
├── Customer_Churned_Analysis_3.ipynb
├── Telco_customer_churn.xlsx
├── customer_churn__dashboard.pbix
├── dashboard.png
├── LICENSE
└── README.md
```

# Tools

- **Python:** Pandas, NumPy, Matplotlib, Seaborn (Jupyter Notebook)
- **Power BI:** DAX, interactive dashboard
- **Data:** Excel

Dolly Yadav

🔗 GitHub: https://github.com/dollyyadavv80-code

