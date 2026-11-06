# Credit Portfolio Analysis

![Dashboard](Credit%20Portfolio%20Analysis_page-0001.jpg)

An interactive Power BI dashboard analyzing credit risk across 10,000 loan records, covering loan purpose, term, home ownership, credit score, and annual income.

## Business Problem
Which loan and customer characteristics are most associated with credit problems, and where should risk screening be tightened?

## Data & Tools
- **Dataset:** `credit_test.csv` (10,000 loan records)
- **Tools:** Power BI, DAX
- **Key metrics:** Total Loan Records, Total Customer, Total Loan Amount (2.74bn), Total Credit Balance (2.91bn), Avg Credit Score (717), Credit Problem Rate (13.5%)

## Process
1. Cleaned and prepared the data in Power BI.
2. Created DAX measures, including Credit Problem Rate.
3. Designed a dashboard with KPI cards, slicers (Purpose, Term, Home Ownership), and 7 visuals.

## Key Findings
- **79%** of loans are for debt consolidation.
- **Buy House** has the highest problem rate (**25.7%**, small sample).
- Problem rate drops from **15.2% (Good)** to **8.3% (Very Good)** credit score band.

## Recommendation
Apply stricter screening (e.g. income or debt-to-income checks) for high-risk loan purposes, and monitor the "Good" credit score band more closely.

## Files
- `Credit Portfolio Analysis.pbix`: Power BI source file
- `Credit Portfolio Analysis.pdf`: dashboard export
- `credit_test.csv`: dataset
