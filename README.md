# retail_sales_analysis
A data analysis project exploring retail transactions, customer demographics, and product categories to uncover sales trends and consumer behavior using pandas and Python.

### 🛒 Retail Transaction Analysis Project
This project is the final assignment for a data analytics course, where I performed a comprehensive analysis of customer shopping behavior using transactional, demographic, and product-level data.

### 🔍 Project Overview
The dataset consists of three main components: transactions, products, and household demographics. I extracted actionable insights into customer behavior over time and across demographic groups through data cleaning, transformation, and exploratory analysis.

### 📊 Key Learnings and Insights
🧹 Data Preparation & Optimization
Loaded large CSV datasets efficiently using selective column import.

Reduced memory usage by converting columns (DAY, QUANTITY, PRODUCT_ID) to optimized integer types, cutting RAM usage by over 22%.

Engineered a proper date column from a DAY index to enable time-based analysis.

📈 Time-Based Sales Analysis
Monthly sales showed fluctuations rather than consistent growth, with noticeable peaks in mid and late 2016.

Comparing 2016 vs 2017 revealed seasonality in sales patterns.

Sales by day of week indicated the highest revenue was generated on Sundays, suggesting weekend shopping is more prevalent.

### 👪 Demographic Insights
Higher total sales were observed among:

Households aged 45-54

Households with higher income brackets ($100K+)

Average sales per household were highest among older adults living with fewer household members, suggesting that smaller households spend more per person.

### 🛍️ Product Category Preferences by Age
By merging all three datasets, I discovered that:

Younger shoppers (19–24) spent disproportionately more on personal care and soft drinks compared to other categories.

Older demographics leaned more heavily into categories like household products and frozen foods.

These insights were exported as a pivot table to Excel for further sharing and reporting.

### 🛠️ Tools & Libraries
Python

pandas, NumPy

Matplotlib

Excel Export for stakeholder-ready outputs

### 📁 Data Source
All data was provided as part of the final project in the Maven Analytics platform's data analytics course.

### ⚠️ Disclaimer
This project was completed for educational purposes only using datasets provided by Maven Analytics as part of their online training platform. I do not own the data, and it should not be used for commercial purposes.
