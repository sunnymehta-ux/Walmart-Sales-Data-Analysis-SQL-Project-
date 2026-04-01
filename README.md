# Walmart-Sales-Data-Analysis-SQL-Project-
This project analyzes Walmart sales data using SQL. The goal is to extract meaningful business insights such as top-performing products, customer behavior, revenue trends, and sales patterns.
🗂️ Dataset Description

The dataset contains transactional sales data with the following key columns:

Invoice ID
Branch & City
Customer Type & Gender
Product Line
Unit Price & Quantity
Total Sales & VAT
Date & Time
Payment Method
Rating
⚙️ Feature Engineering

New columns were created to enhance analysis:

time_of_day → Morning / Afternoon / Evening
day_name → Monday to Sunday
month_name → January to December
📊 Key Business Questions Answered
🔹 Product Analysis
Top 3 most selling product lines
Product line with highest revenue
Product line with highest VAT
Product performance (Good / Bad based on avg sales)
🔹 Sales Analysis
Sales distribution by time of day & weekday
City with highest revenue
Branch performance comparison
🔹 Customer Insights
Customer type generating highest revenue
Most common payment method
Time of day with highest customer ratings
📈 Key Insights
Evening time has the highest customer engagement
Certain product lines dominate revenue generation
Payment methods show clear customer preference trends
Sales patterns vary significantly across weekdays
🛠️ Tools Used
MySQL
SQL (Joins, Aggregations, Window Functions)

Project Structure
├── dataset/
├── queries.sql
├── README.md
💡 Future Improvements
Dashboard using Power BI / Tableau
Advanced analytics (customer segmentation)
Time-series sales forecasting

Author
Sunny Mehta
