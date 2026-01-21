# 🍕 Pizza Sales Intelligence System (Excel)

## 🧩 Problem  
Raw sales data contained inconsistent formats, missing values, and unstructured order records.  
Using this data directly would produce misleading revenue trends and unreliable performance metrics.

## 🎯 Objective  
Transform messy transactional data into a clean, structured reporting layer that produces accurate, repeatable sales insights for business use.

## 🚨 Data Issues Identified  
- Inconsistent date and currency formats  
- Missing values in key fields  
- Unstructured order-level data  
- Duplicate or partial records  
- Totals not matching across sheets  

## 🛠️ Approach  
1. Isolated raw data from working layers  
2. Normalized formats (dates, currency, categories)  
3. Cleaned and standardized product and order fields  
4. Built structured Pivot-based reports  
5. Created validation checks for totals and record counts  
6. Designed repeatable summaries for daily and monthly use  

## 🛡️ Validation & Control Logic  
- Row-count and completeness checks  
- Revenue reconciliation across views  
- Category consistency checks  
- Formula-based guards for silent errors  

Any mismatch triggers a review before results are used.

## 📊 Output  
- Clean transactional dataset  
- Revenue and order trend summaries  
- Performance views by product and category  
- Business-ready Excel reports  

## 💡 Why This Matters  
Sales data changes every day.  
A report that works once but breaks silently later is dangerous.

This system is built to:  
- Expect messy inputs  
- Enforce structure  
- Surface inconsistencies  
- Deliver numbers that can be trusted  

The goal is not charts.  
The goal is **reliable business decisions**.

## 🧰 Tools Used  
- **MS Excel** – Data Cleaning, Standardization, Pivot Tables, Validation, Reporting  
