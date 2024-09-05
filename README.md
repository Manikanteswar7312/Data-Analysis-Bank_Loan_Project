**BANK LOAN DATA ANALYSIS PROJECT**
 
**Project Overview**
This project aims to provide a comprehensive overview of a financial institution's lending operations, focusing on loan applications, disbursements, and portfolio health. The project uses detailed data analysis and visualizations to assess key performance indicators (KPIs) such as total loan applications, funded amounts, amount received, interest rates, and debt-to-income (DTI) ratios. The analysis covers trends over time, regional differences, and borrower characteristics, with the ultimate goal of providing actionable insights into the loan portfolio's performance.

 **Problem Statement**
The primary objective is to develop a dashboard that allows stakeholders to monitor loan operations in a categorized, structured way. The dashboard will offer insights into:
 Total Loan Applications
 Total Funded Amount
 Total Amount Received
 Month-to-Date (MTD) Metrics for Loans, Funds, and Repayments
 Average Interest Rate
 Average Debt-to-Income (DTI) Ratio

The solution includes key analyses such as:
1. Monthly Trends by Issue Date to observe seasonal and long-term trends.
2. Regional Analysis to assess lending activity by state.
3. Home Ownership Analysis to evaluate the impact of ownership status on loan disbursements and applications.
4. Loan Term and Purpose Breakdown to understand how loan duration and purpose affect performance.

 **Key Features**
  KPI Tracking: Visualizations for total loan applications, total funded amounts, and total amounts received, updated month-to-date (MTD) and shown in trends over time.
  Interest Rate Monitoring: Provides average interest rates across various loan categories and tracks month-over-month (MoM) changes.
  Debt-to-Income Ratio (DTI): Shows average DTI for different loan types, purposes, and borrower profiles.
  Trend Analysis: Highlights seasonal trends in lending activities by analyzing data by issue date.
  Regional Insights: Offers state-wise lending insights to uncover areas of high and low activity.
  Loan Purpose and Term Analysis: Breaks down loans by term length and purpose to identify patterns in loan applications and disbursements.

 **Data Used**
The dataset includes 38,576 entries and the following key columns:
  Loan Information: loan_amount, installment, int_rate, loan_status, purpose, grade, sub_grade, term, issue_date.
  Borrower Information: annual_income,dti,home_ownership,emp_length,emp_title,address_state.
  Repayment Information: total_payment,last_payment_date,next_payment_date,last_credit_pull_date.

**Major Factors Influencing Loan Status**
  The project identifies key factors that influence whether a loan is categorized as good or bad, based on historical data and industry experience:**Interest Rate**: Higher 
  interest rates are generally associated with bad loans, while lower rates correspond to good loans.
  Loan Purpose: Certain loan purposes (e.g., "Debt consolidation", "Medical") are considered riskier, while others (e.g., "Home improvement") show stronger repayment 
  performance.
  Debt-to-Income Ratio (DTI): A higher DTI is a strong indicator of financial stress, often correlating with higher loan default rates.
    
**Visualization Requirements for Power BI Dashboard**
  To display these insights effectively, the following visualizations are required:
  1. Monthly Trends by Issue Date (Line Plot): To identify seasonal and long-term trends in loan applications.
  2. Regional Analysis by State (Stacked Bar Chart): To assess regional disparities in loan applications and disbursements.
  3. Home Ownership Analysis (Stacked Bar Chart): To understand how home ownership impacts loan applications and disbursements.
  4. Loan Term Analysis (Pie Chart): To visualize the distribution of loans by term length.
  5. Loan Purpose Breakdown (Bar Chart): To show how loan purposes contribute to overall loan applications and disbursements.


 **Technologies Used**:
   Python: For data analysis (pandas, NumPy, Matplotlib).
   Power BI: For interactive data visualizations.
   Jupyter Notebook: For exploratory data analysis (EDA).
  
**Conclusion**:
This project provides critical insights into the health of the lending portfolio, enabling data-driven decision-making. The dashboard offers a holistic view of loan performance, from regional trends to loan purpose analysis, empowering stakeholders to take informed actions to improve portfolio management and risk assessment.

