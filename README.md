Product Returns & Refund Analysis
Overview
This Data Analytics project explores e-commerce orders and product returns using Python, SQL, and Power BI.
Dataset summary
Orders: 15,000 rows
Returns: 3,200 rows
Products: 1,200 rows
Customers: 4,000 rows
Verified findings
Simple return-to-order ratio: 3,200 / 15,000 = 21.33%
Most common reason: Size/Fit Issue — 591 (18.47%)
Next: Changed Mind — 473 (14.78%)
Return status Refunded: 2,234 (69.81%)
Approved - Pending Refund: 406 (12.69%)
Data quality note
A refund amount discrepancy was observed: Python/source CSV contains positive refund values, but the imported MySQL `returns` table showed all values as 0.00. Do not publish refund totals/averages until this is resolved.
Repository structure
`Project_Report.docx` — project report
`python/` — Python chart script
`sql/` — SQL analysis queries
`power_bi/` — dashboard build guide and DAX measures
`data/` — place cleaned CSV files here only if your instructor permits sharing them
`charts/` — save exported chart PNGs here
How to run
Install Python and the packages listed in `python/requirements.txt`.
Update the CSV paths in `python/create_charts.py` to match your machine.
Run the script and save the generated charts.
Open Power BI Desktop, import the cleaned CSVs, create relationships as described in `power_bi/Dashboard_Guide.md`, and save the `.pbix` file in `power_bi/`.
Review the report and update the final observations based on your actual chart output.
Privacy and academic integrity
Do not upload personal, confidential, or restricted data. Confirm your instructor's rules before publishing datasets. Replace placeholders with your name, course, and submission date.
