SQL Data Cleaning & Exploratory Data Analysis – Layoffs Dataset Project Overview This project showcases a complete end-to-end data preparation and analysis process using SQL only.
I worked on a real-world layoffs dataset to first clean the data using SQL and then performed Exploratory Data Analysis (EDA) — all within MySQL, without using Excel or Python. The goal was to take a raw, messy dataset and turn it into an analysis-ready format, then derive meaningful insights directly using SQL queries.

Phase 1: Data Cleaning (cleaning_queries.sql) Key operations performed:

✅ Removed duplicate rows using ROW_NUMBER() and CTEs
✅ Handled NULL and blank values in industry, layoff counts, and other fields
✅ Trimmed inconsistent text entries (like trailing dots and mixed casing)
✅ Standardized country and industry names
✅ Converted string-based date columns into proper SQL DATE format
✅ Dropped unnecessary columns (like helper row_num)
All these queries are available in: cleaning_queries.sql

Phase 2: Exploratory Data Analysis (eda_queries.sql) Key insights generated through SQL queries:

Most affected industries by total layoffs
Top countries with the highest number of layoffs
Companies with multiple rounds of layoffs
Layoff trends over time using grouped dates
Industry and country-wise breakdown using GROUP BY, ORDER BY, HAVING, and aggregate functions All EDA queries are available in: eda_queries.sql
Tools & Technologies

MySQL
SQL Queries – DDL, DML, CTEs, Window Functions, Aggregates, Filtering
No external tools — full project handled using SQL inside MySQL Workbench
What I Learned

How to clean real-world data using structured SQL logic
Writing efficient queries for grouping, aggregation, and filtering
Applying analytical thinking using only SQL — no Python or Excel
Structuring data projects in a clean and professional format
Final Note This project proves that "SQL alone can handle both cleaning and analysis of data", making it an incredibly powerful tool for any aspiring data analyst. Thanks for visiting!
Stay tuned — more SQL and data analysis projects coming soon 🚀
