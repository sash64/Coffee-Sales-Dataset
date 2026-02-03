## About the Project

I worked with a coffee sales dataset consisting of **Products, Orders, and Customers** tables. The goal was to clean the data and prepare it for analysis and dashboards.

**What I did:**  
1. **Cleaned column names** – removed spaces and made them SQL-friendly (e.g., `Coffee Type` → `CoffeeType`). I could have done this in Excel before importing, but I did it in SQL for a bit of extra practice and fun.  
2. **Handled missing data** – some fields like `Email` and `PhoneNumber` were empty. I used `NULLIF` and `IFNULL` in SQL to replace empty strings with `'N/A'`, so the data is consistent and dashboard-ready.  
3. **Joined tables** – combined Orders, Products, and Customers into a single dataset using `CustomerID` and `ProductID` as keys.  
4. **Calculated metrics** – created `TotalPrice` and `TotalProfit` for each order to make analysis easier.

The final table is clean, complete, and ready for dashboards or further analysis. A dashboard using this dataset will be coming soon!

## Data & SQL Files

- `Messy Dataset for Coffee Sales/` → original messy CSV files  
- `Clean Dataset for Coffee/` → cleaned tables and the joined FullData table  
- `Coffee Dataset SQL Code/` → SQL queries used to clean and join the data

