AMAZON INDIA SALES ANALYTICS PROJECT
=====================================

Project objective
Create a management-friendly view of sales, profitability, category/product performance,
order status, payment methods, fulfillment methods, and state-level performance.

Files
- Amazon_India_Sales_Analytics_Project.xlsx: Excel dashboard, cleaned data, and summary tabs.
- Amazon_India_Project_Report.pdf: project report with methodology, KPI definitions, and key observations.
- Amazon_India_Sales_Cleaned.csv: cleaned source rows.

Source and scope
- Input was the supplied Amazon Sales Data India Google Sheets HTML export.
- 99 order records were parsed from the supplied export.
- Dates range from 2024-01-02 to 2026-08-15.
- Amounts were parsed from rupee-formatted text into numeric INR values.
- Discount_Pct was converted from percentage text to a decimal fraction.
- No external data was added.

Core KPI definitions
- Total Sales = sum of Total_Sales_INR.
- Total Profit = sum of Profit_INR.
- Total Orders = distinct Order_ID count.
- Units Sold = sum of Quantity.
- Average Order Value = Total Sales / distinct Order_ID count.
- Profit Margin = Total Profit / Total Sales.
- Return Rate = Returned orders / distinct orders.
- Cancellation Rate = Cancelled orders / distinct orders.

Important limitation
The supplied data contains order-level records but no explicit customer ID or cost breakdown.
Profit and sales are taken as provided; the report does not independently validate them.
The data is a small supplied extract, so conclusions should not be treated as a complete picture of Amazon India.
