# UPI Transaction and Fraud Risk Analysis

## About
Capstone project analyzing 25K UPI transactions to identify fraud patterns, built as a Power BI dashboard with a written report.

## Files
- `upi_transaction_Dataset.xlsx`: dataset used
- `UPI_Transaction_Detection.pbix`: Power BI dashboard (open with Power BI Desktop)
- `UPI_Transaction_And_Fraud_Risk_Analysis_CP1.pdf`: dashboard PDF (open directly in browser)
- `UPI Transactions and Fraud Risk Analysis_CP1- Project Report.pdf`: written project report

## Dashboard pages
- Overview: KPI cards, monthly trend, fraud vs legitimate, city and payment app analysis
- Risk Signals: fraud amount by transaction type, payment app risk ranking, city-wise fraud
- Transactions: transaction details table, fraud map by city, fraud rate gauge

## Tools used
- Excel, Power BI

## Key insights
- Out of 25K transactions, about 4.24K were fraudulent, giving a fraud rate of 16.96%.
- Fraud transactions made up around ₹7.5M of the ₹21.5M total transaction amount, so fraud is costly even though it is a smaller share of the count.
- P2P transactions had the highest fraud amount (₹3.19M), followed by P2M (₹2.55M), Bill Payment (₹1.21M) and Recharge (₹0.59M).
- Google Pay (35.06%) and PhonePe (34.87%) account for about 70% of all fraud cases, mainly because they handle the most transactions.
- BHIM has the highest fraud rate (around 17.8%) among payment apps, even though its transaction volume is low.
- Delhi had the highest fraud amount (₹1.04M), followed by Kolkata (₹1.00M) and Chennai (₹0.97M). Fraud is spread fairly evenly across cities.
- Monthly transactions stayed between about 1.9K and 2.2K, with a peak in July and a low in February.

## Author
Swapna Yadav
