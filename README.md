# Customer Churn Analysis (Python + Power BI)

Customer Churn Analysis using Python + Power BI is a data analytics project focused on understanding customer churn patterns. Python and Pandas were used for data cleaning and EDA, while Power BI was used to create an interactive dashboard and generate meaningful business insights.

Show Image

Objective
Understand who is leaving, when, and why, so the business can focus retention efforts on the right customers.

Tools & Technologies
Area	Tools
Data cleaning & EDA	Python, Pandas, NumPy, Matplotlib, Seaborn (Jupyter Notebook)
Dashboard	Power BI, DAX
Data format	Excel (.xlsx)
Dataset
IBM Telco Customer Churn sample dataset.

7,043 customers and 33 columns
Covers demographics, location, services subscribed, contract type, billing, tenure, monthly/total charges, churn label, and churn reason
Project Workflow
Data cleaning (Python)
Converted Total Charges from text to numeric (blank values were stored as spaces)
Handled missing values; filled Churn Reason with "Not Churned" for retained customers
Checked customers with 0 tenure months (new customers with no billing yet)
Exploratory data analysis (Python)
Churn distribution, churn by contract type, total charges vs churn, correlation heatmap, top churn reasons
Export cleaned data
Saved as Telco_customer_churn_cleaned.xlsx
Dashboard (Power BI)
Loaded the cleaned data, created measures (Total Customers, Churn Customers, Churn Rate %), tenure groups and customer type, and built the visuals
Dashboard Overview
KPIs

Total customers: 7,043
Churned customers: 1,869
Churn rate: 26.54%
Visuals

Churn customers by contract type
Churn rate by tenure group (0-12, 13-24, 25+ months)
Monthly charges by customer type
Monthly charges by Online Security and Online Backup
Customer retention (churned vs retained)
Average monthly charges by churn label
Slicers for Gender and Customer Type
Key Insights
About 1 in 4 customers churned (26.54% churn rate).
Month-to-month contracts have far more churn than one-year and two-year contracts.
New customers are the most at risk. Churn is highest in the 0-12 month tenure group and drops as tenure increases.
Tenure has the strongest link to churn among the numeric features. Longer-tenured customers churn less.
Top churn reasons include the attitude of support staff and competitors offering higher download speeds.
Recommendations
Offer incentives to move month-to-month customers onto longer contracts.
Build an onboarding and follow-up program for customers in their first 12 months.
Improve support staff training and service quality.
Review internet speed plans against competitor offerings.
Repository Structure
customer-churn-analysis/
├── data/
│   ├── Telco_customer_churn.xlsx
│   └── Telco_customer_churn_cleaned.xlsx
├── notebooks/
│   └── Customer_Churned_Analysis.ipynb
├── powerbi/
│   └── Customer_Churn_Dashboard.pbix
├── images/
│   └── dashboard.png
├── requirements.txt
└── README.md
How to Run
Python notebook

bash
git clone https://github.com/<your-username>/customer-churn-analysis.git
cd customer-churn-analysis
pip install -r requirements.txt
jupyter notebook notebooks/Customer_Churned_Analysis.ipynb
Power BI dashboard

Open powerbi/Customer_Churn_Dashboard.pbix in Power BI Desktop
If prompted, point the data source to data/Telco_customer_churn_cleaned.xlsx
requirements.txt
pandas
numpy
matplotlib
seaborn
openpyxl
jupyter
Author
Your Name LinkedIn | GitHub





