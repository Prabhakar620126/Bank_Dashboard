# Bank_Dashboard
A project for analyzing bank performance metrics with interactive charts in PowerBI, Excel , SQL and  Python.

### Raw Data for project :-
  <a href="https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/financial_loan.csv"> CSV data file </a>
### PROBLEM STATEMENT
   Key Performance Indicators (KPIs) Requirements:
  Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).
  Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.
  Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.
  Average Interest Rate: Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.
  Average Debt-to-Income Ratio (DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans, MTD, and track Month-over-Month (MoM) fluctuations.
  
Good Loan v Bad Loan KPI’s

Good Loan:
Good Loan Application Percentage
Good Loan Applications
Good Loan Funded Amount
Good Loan Total Received Amount

Bad Loan
Bad Loan Application Percentage
Bad Loan Applications
Bad Loan Funded Amount
Bad Loan Total Received Amount

Loan Status Grid View
In order to gain a comprehensive overview of our lending operations and monitor the performance of loans, we aim to create a grid view report categorized by 'Loan Status.’ By providing insights into metrics such as 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'Month-to-Date (MTD) Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI),' this grid view will empower us to make data-driven decisions and assess the health of our loan portfolio.

### DASHBOARD 2: OVERVIEW

CHARTS
Monthly Trends by Issue Date (Line Chart):  To identify seasonality and long-term trends in lending activities
Regional Analysis by State (Filled Map): To identify regions with significant lending activity and assess regional disparities
Loan Term Analysis (Donut Chart): To allow the client to understand the distribution of loans across various term lengths.
Employee Length Analysis (Bar Chart): How lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.
Loan Purpose Breakdown (Bar Chart): Will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.
Home Ownership Analysis (Tree Map): For a hierarchical view of how home ownership impacts loan applications and disbursements.
Metrics to be shown: 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

### DASHBOARD 3: DETAILS
Need for a comprehensive 'Details Dashboard' that provides a consolidated view of all the essential information within our loan data. This Details Dashboard aims to offer a holistic snapshot of key loan-related metrics and data points, enabling users to access critical information efficiently.

## TERMINOLOGIES USED IN DATA
Fields Used in Data
### Loan ID:
  Purpose: Loan ID is a unique identifier assigned to each loan application or loan account. It serves as a primary key for tracking and managing individual loans.
  Use for Banks: Banks use Loan IDs to efficiently manage and track loans throughout their lifecycle. It aids in organizing loan records, monitoring repayments, and addressing customer inquiries.
### Address State:
  Purpose: Address State indicates the borrower's location. It helps in assessing regional risk factors, compliance with state regulations, and estimating default probabilities.
  Use for Banks: Banks use this information to identify regional trends in loan demand, adjust marketing strategies, and manage risk portfolios based on geographic regions.
### Employee Length:
  Purpose: Employee Length provides insights into the borrower's employment stability. Longer employment durations may indicate greater job security.
  Use for Banks: Banks consider employment length when assessing a borrower's ability to repay. Stable employment often translates to a lower default risk.
### Employee Title:
  Purpose: Employee Title specifies the borrower's occupation or job title. It helps lenders understand the source of the borrower's income.
  Use for Banks: Banks use this field to verify income sources, assess the borrower's financial capacity, and tailor loan offers to different professions.
### Grade:
  Purpose: Grade represents a risk classification assigned to the loan based on creditworthiness. Higher grades signify lower risk.
  Use for Banks: Banks use the grade to price loans and manage risk. Higher-grade loans typically receive lower interest rates and are more attractive to investors.

### Sub Grade:
  Purpose: Sub Grade refines the risk assessment within a grade, providing additional risk differentiation.
  Use for Banks: Sub Grades offer a finer level of risk assessment, helping banks tailor interest rates and lending terms to match borrower risk profiles.
### Home Ownership:
  Purpose: Home Ownership indicates the borrower's housing status. It offers insights into financial stability.
  Use for Banks: Banks use this field to assess collateral availability and borrower stability. Homeowners may have lower default rates.
### Issue Date:
  Purpose: Issue Date marks the loan's origination date. It's crucial for loan tracking and maturity calculations.
  Use for Banks: Banks use Issue Dates to track loan aging, calculate interest accruals, and manage loan portfolios
### Last Credit Pull Date:
  Purpose: Last Credit Pull Date records when the borrower's credit report was last accessed. It helps monitor creditworthiness.
  Use for Banks: Banks use this date to track credit history updates, assess credit risk, and make informed lending decisions.
### Loan Status:
  Purpose: Loan Status indicates the current state of the loan (e.g., fully paid, current, default). It tracks loan performance.
  Use for Banks: Banks use Loan Status to monitor loan health, categorize loans for risk analysis, and determine provisioning requirements.

### Loan Status:
  Purpose: Loan Status indicates the current state of the loan (e.g., fully paid, current, default). It tracks loan performance.
  Use for Banks: Banks use Loan Status to monitor loan health, categorize loans for risk analysis, and determine provisioning requirements.

### Purpose:
  Purpose: Purpose specifies the reason for the loan (e.g., debt consolidation, education). It helps understand borrower intentions.
  Use for Banks: Banks use this field to segment and customize loan offerings, aligning loan terms with borrower needs
### Term:
  Purpose: Term defines the duration of the loan in months. It sets the repayment period.
  Use for Banks: Banks use the term to structure loan agreements, calculate interest payments, and manage loan maturities
### Verification Status:
  Purpose: Verification Status indicates whether the borrower's financial information has been verified. It assesses data accuracy.
  Use for Banks: Banks use this field to gauge data reliability, verify income, and evaluate loan application credibility.

### Annual Income:
  Purpose: Annual Income reflects the borrower's total yearly earnings. It assesses repayment capacity.
  Use for Banks: Banks use this income figure to determine loan eligibility, calculate debt-to-income ratios, and evaluate creditworthiness.
### DTI (Debt-to-Income Ratio):
  Purpose: DTI measures the borrower's debt burden relative to income. It gauges the borrower's capacity to take on additional debt.
  Use for Banks: Banks use DTI to assess a borrower's ability to handle loan payments and make responsible lending decisions.

### Instalment:
  Purpose: Instalment is the fixed monthly payment amount for loan repayment, including principal and interest.
  Use for Banks: Banks use this field to structure loan terms, calculate amortization schedules, and assess payment affordability.

### Interest Rate:
  Purpose: Interest Rate represents the annual cost of borrowing expressed as a percentage. It determines the loan's cost.
  Use for Banks: Banks use interest rates to price loans, manage profit margins, and attract investors.

### Loan Amount:
  Purpose: Loan Amount is the total borrowed sum. It defines the principal amount.
  Use for Banks: Banks use Loan Amount to determine loan size
  
# Final Result 
  ## DASHBOARD  POWERBI 
  - <a href="https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/bank%20power%20bi.pbit"> Dashboard</a>
  - <a href="https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Summery_dashboard.png"> Summary Dashboard </a>
  - <a href="[https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Summery_dashboard.png](https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Overview_dashboard.png)"> Overview Dashboard </a>
  <a href="[[https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Summery_dashboard.png](https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Overview_dashboard.png)](https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Overview_dashboard.png)"> Details Dashboard </a>
  
### SQL Query:
* ✅<a herf="https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Bank_DashBoard_sql.docx"> Query </a>

### Python code 
* ✅<a herf="https://github.com/Prabhakar620126/Bank_Dashboard/blob/main/Bank%20Loan%20Project.ipynb"> python </a>
