This is a project-based internship organized by Rakamin. The project aims to analyze drug sales data from Kimia Farma using Google BigQuery and visualize it through Google Looker Studio.

Data Process:
- Data is combined using JOIN between tables with a CTE (Common Table Expressions) approach to maintain query readability and structure.
- A main analysis table is created: tabel_analisa, which includes transaction data, product information, branch details, and sales specifics.
- Calculations are performed for new columns, such as:
  * nett_sales: Price after discounts
  * persentase_gross_laba: Gross profit margin percentage based on price
  * nett_profit: Net profit per transaction

This is the final dashboarding using Google Looker Studio: https://lookerstudio.google.com/s/lbcAbM6Xyzo 
