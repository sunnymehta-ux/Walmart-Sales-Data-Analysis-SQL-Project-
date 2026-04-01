# 🛒 Walmart Sales Data Analysis (SQL Project)

## 📌 Project Overview

This project analyzes Walmart sales data using SQL to uncover meaningful business insights such as product performance, customer behavior, and revenue trends.

---

## 🗂️ Dataset Description

The dataset contains transactional sales data with the following fields:

* Invoice ID
* Branch & City
* Customer Type & Gender
* Product Line
* Unit Price, Quantity, VAT, Total
* Date & Time
* Payment Method
* Rating

---

## ⚙️ Feature Engineering

New columns were created to improve analysis:

* **time_of_day** → Morning / Afternoon / Evening
* **day_name** → Monday to Sunday
* **month_name** → January to December

---

## 📊 Key Business Questions

### 🔹 Product Analysis

* Top 3 most selling product lines
* Product line with highest revenue
* Product line with highest VAT
* Product performance (Good / Bad based on average sales)

### 🔹 Sales Analysis

* Sales distribution by time of day and weekday
* City with highest revenue
* Branch performance comparison

### 🔹 Customer Insights

* Customer type generating highest revenue
* Most common payment method
* Time of day with highest customer ratings

---

## 📈 Key Insights

* 🌆 Evening has the highest customer engagement
* 🛍️ Certain product lines dominate revenue
* 💳 Payment methods show clear preferences
* 📅 Sales vary significantly across weekdays

---

## 🛠️ Tools & Skills

* MySQL
* SQL (GROUP BY, CASE, Aggregations, Window Functions)

---

## 🚀 How to Run

```sql
CREATE DATABASE salesdatawalmart;
```

1. Import dataset into `sales` table
2. Run queries from `queries.sql`

---

## 📂 Project Structure

```
📁 dataset/
📄 schema.sql
📄 advacnced.sql
📄 queries.sql
📄 README.md
```

---

## 💡 Future Improvements

* Dashboard using Power BI / Tableau
* Customer segmentation
* Sales forecasting

---

## 👨‍💻 Author

Sunny Mehta
(Add your LinkedIn & GitHub link here)
