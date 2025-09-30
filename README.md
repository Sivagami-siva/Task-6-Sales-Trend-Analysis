# 📊 Online Sales Analysis using SQLite

This project demonstrates **basic SQL queries** for analyzing online sales data using **SQLite**.  
The dataset contains `30+` rows of sample sales records with fields like `order_id`, `customer_id`, `product_id`, `quantity`, `amount`, and `order_date`.

---

## ⚡ Steps Performed

1. **Data Preparation**  
   - Imported CSV file (`online_sales_30.csv`) into SQLite.  
   - Extracted `Year` and `Month` from the `order_date` column.

2. **Analysis Queries**  
   - **Monthly Revenue** → `SUM(amount)` grouped by year & month.  
   - **Monthly Order Volume** → `COUNT(DISTINCT order_id)` grouped by year & month.  
   - **Combined Report** → Monthly revenue & order volume together.  

3. **Insights**  
   - Identified sales trends across months.  
   - Observed variations in revenue and order volume over time.  

---

## 🛠️ Tools Used
- **SQLite** (DB Browser for SQLite)  
- **CSV dataset** (`online_sales_30.csv`)  

---

## 🚀 How to Run
1. Open DB Browser for SQLite.  
2. Import `online_sales_30.csv` into a new database.  
3. Run the SQL queries from `queries.sql`.  
4. View results in the **Browse Data** or **Execute SQL** tabs.  
