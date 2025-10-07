💰 Bank Loan Analysis Project

📊 Overview
The Bank Loan Analysis project is a data analytics case study designed to assess and visualize the performance of a bank’s loan portfolio.  
Using MS SQL Server for backend data querying and Power BI for dashboard visualization, the project uncovers insights into loan distribution, borrower profiles, and repayment performance.  
This analysis helps financial institutions identify trends, measure risk, and make data-driven lending decisions.

🧰 Tools & Technologies
- MS SQL Server 
- SQL Server Management Studio (SSMS) 
- Power BI 

⚙️ Project Workflow
1. Data Import & Cleaning
   - Imported the raw dataset into MS SQL Server
   - Cleaned and structured data for consistency.

2. Database & Query Creation
   - Created database and tables (`bank_loan_data`).
   - Wrote SQL queries to extract and analyze KPIs.

3. Power BI Integration
   - Connected Power BI to SQL Server.
   - Built interactive dashboards for visualization.

🧮 Key Performance Indicators (KPIs)
KPI Description 

Total Loan Applications (Total number of loan requests.) 
Total Funded Amount (Sum of all disbursed loans.) 
Total Amount Received (Total repayments collected.) 
Average Interest Rate (Mean loan interest rate.) 
Average Debt-to-Income (DTI Measures borrower financial health.)
Good Loan Metrics (% and count of “Fully Paid” or “Current” loans.)
Bad Loan Metrics (% and count of “Charged Off” loans.)


📈 Power BI Dashboards
🟢 Dashboard 1: Summary
A KPI-driven summary featuring:
- Total & Month-to-Date (MTD) metrics for applications, funded amounts, and repayments.
- Month-over-Month (MoM) comparisons.
- Good vs. Bad Loan breakdown.
- Loan Status grid with Interest Rate & DTI overview.

🔵 Dashboard 2: Overview
Visualizes trends and distributions:
- Monthly Loan Trends (Line Chart)
- Loan Term Distribution (Donut Chart)
- Employee Length Breakdown (Bar Chart)
- Loan Purpose Analysis (Bar Chart)
- Home Ownership Impact (Tree Map)

🟣 **Dashboard 3: Details
A comprehensive grid view showing:
- All essential borrower and loan metrics.
- Filters for dynamic insights.
- One-stop access for performance and profile analytics.

🧠 SQL Concepts Used
- `SELECT`, `GROUP BY`, `ORDER BY`, `COUNT`, `SUM`, `AVG`, `ROUND`
- Conditional aggregations using `CASE WHEN`
- Date functions: `DATENAME()`, `MONTH()`, `YEAR()`
- Subqueries, CTEs, and Partitioning

📊 Power BI Techniques
- Power Query transformations  
- DAX measures for KPIs  
- Time intelligence (MTD, PMTD, MoM calculations)  
- Slicers, Filters, and Navigation buttons  
- KPI Cards, Bar/Line/Tree/Map visuals  

 💡 Insights
- Loan applications peak in specific months, revealing seasonal lending trends.  
- Good loans dominate the portfolio, ensuring strong repayment rates.  
- Bad loans highlight areas of risk, aiding credit strategy improvements.  
- Borrower employment length and home ownership show correlation with repayment behavior.  





