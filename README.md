# Module-1-end-assignment_ecommerce

# E-Commerce Sales Analytics Project

## Project Overview

This project analyzes an E-Commerce Sales dataset to identify business insights related to customers, products, stores, sales performance, regions, and payment methods.

The dataset was prepared using dimensional modeling concepts and analyzed using Microsoft Excel. The project covers four types of analytics:

* Descriptive Analytics
* Diagnostic Analytics
* Predictive Analytics
* Prescriptive Analytics

The main objective of this project is to understand historical sales performance, identify factors affecting sales, predict future trends, and provide business recommendations.

---

## Dataset Structure

The workbook contains the following tables:

### Customer_Dim

Contains customer-related information:

* Customer ID
* Customer Name
* Age
* Gender
* City
* State
* Country

### Product_Dim

Contains product-related information:

* Product ID
* Product Name
* Category
* Sub Category
* Brand
* Cost
* Stock

### Store_Dim

Contains store-related information:

* Store ID
* Store Name
* Region
* City
* Store Type

### Sales_Fact

Contains transactional sales data:

* Sales ID
* Order Date
* Customer ID
* Product ID
* Store ID
* Quantity
* Unit Price
* Discount
* Payment Type
* Total Amount

### Merged Table

A consolidated table created by joining the Sales Fact table with the Customer, Product, and Store dimension tables.

The merged table was used as the primary source for analysis and reporting.

---

## Data Preparation

The following data preparation activities were performed:

* Standardized Customer IDs by replacing prefixes with "CUST".
* Standardized Product IDs by replacing prefixes with "PROD".
* Handled missing values using Excel formulas.
* Merged Fact and Dimension tables for analysis.
* Validated data consistency across all tables.
* Prepared the consolidated dataset for reporting and analysis.

---

# Analytics Performed

## 1. Descriptive Analytics

### Objective

To understand historical business performance and identify important patterns in the sales data.

### Analysis Performed

* Revenue by product category
* Revenue by store
* Revenue by city
* Revenue by payment method
* Customer demographics analysis
* Gender-wise customer analysis
* Year-wise revenue trends
* Product sales performance

### Analysis Sheets

* Category vs Sales
* Store vs Sales
* City vs Sales
* Payment Type vs Sales
* Customer vs Gender
* Year vs Revenue

### Business Questions

* Which product categories generate the highest revenue?
* Which stores contribute the most to sales?
* Which cities generate higher revenue?
* Which payment methods are most commonly used?
* How does revenue change over time?

---

## 2. Diagnostic Analytics

### Objective

To identify the factors influencing sales performance and understand why certain products, stores, and customer segments perform better.

### Analysis Performed

* Product contribution to revenue
* Regional store distribution
* Store performance comparison
* Customer purchase patterns
* Impact of discounts on revenue
* Category-level performance

### Business Questions

* Why do certain categories generate more revenue?
* Which stores contribute most to sales?
* Which products drive business growth?
* Which customer segments generate the highest revenue?
* How do discounts affect sales performance?

---

## 3. Predictive Analytics

### Objective

To identify future sales trends using historical data.

### Analysis Performed

* Revenue trend analysis
* Demand pattern identification
* Product sales forecasting
* Customer buying behavior assessment
* Future growth opportunity analysis
* Forecasting using Excel Forecast Sheet

### Predictions

* High-performing products are likely to continue driving sales.
* Digital payment methods may continue to gain adoption.
* Top-performing stores are likely to maintain strong performance.
* Revenue may remain stable or grow if current trends continue.

These predictions are based on historical data patterns and should be treated as indicative rather than guaranteed outcomes.

---

## 4. Prescriptive Analytics

### Objective

To provide actionable recommendations based on the analysis results.

### Recommendations

* Increase inventory for high-demand products.
* Monitor stock levels of top-selling products.
* Expand operations in high-performing regions.
* Promote digital payment methods.
* Implement customer loyalty programs.
* Optimize discount strategies.
* Focus marketing campaigns on top-performing categories.
* Analyze and improve underperforming stores and products.

---

# Key Performance Indicators (KPIs)

The following KPIs were considered for evaluating business performance:

* Total Revenue
* Total Sales Transactions
* Average Order Value
* Product Sales Volume
* Category Revenue Contribution
* Store Performance
* Customer Distribution
* Payment Method Performance

### Average Order Value

Average Order Value can be calculated as:

**AOV = Total Revenue / Number of Sales Transactions**

---

# Tools Used

* Microsoft Excel
* Excel Pivot Tables
* Excel Pivot Charts
* Excel Forecast Sheet
* Excel Data Analysis ToolPak
* XLOOKUP
* Excel formulas
* Data Cleaning Techniques
* Data Transformation Techniques

---

# Project Workflow

Raw E-Commerce Data
↓
Data Cleaning
↓
ID Standardization
↓
Missing Value Handling
↓
Fact & Dimension Tables
↓
Data Merging
↓
Consolidated Dataset
↓
Pivot Tables & Charts
↓
Descriptive Analytics
↓
Diagnostic Analytics
↓
Predictive Analytics
↓
Prescriptive Analytics
↓
Business Recommendations

---

# Key Business Insights

The analysis provides insights into:

* Overall revenue performance
* Best-performing product categories
* Top-performing products
* Store and regional performance
* Customer purchasing patterns
* Payment method preferences
* Sales trends over time
* Future revenue trends
* Inventory and marketing opportunities

---

# Business Recommendations

Based on the analysis, the following recommendations can be considered:

1. Maintain sufficient inventory for high-demand products to reduce potential stockouts.

2. Focus marketing and promotional activities on high-performing product categories.

3. Analyze successful stores and apply their strategies to lower-performing locations.

4. Introduce customer loyalty programs and targeted promotions based on customer purchasing behavior.

5. Optimize discount strategies to increase sales while maintaining profitability.

6. Promote digital payment methods to improve customer convenience and adoption.

---

# Project Structure

E-Commerce-Sales-Analytics/

├── Ecommerce dataset.xlsx
├── README.md
└── Analysis/

```
├── Descriptive Analytics
├── Diagnostic Analytics
├── Predictive Analytics
└── Prescriptive Analytics
```

---

# Conclusion

This E-Commerce Sales Analytics project demonstrates how Microsoft Excel can be used to transform transactional sales data into meaningful business insights.

The project combines data cleaning, data preparation, dimensional modeling, Pivot Tables, statistical analysis, visualization, forecasting, and business recommendations.

The analysis provides a comprehensive view of sales performance across products, customers, stores, regions, and payment methods and helps support data-driven business decision-making.

---

# Skills Demonstrated

* Data Cleaning
* Data Preparation
* Microsoft Excel
* Pivot Tables
* Pivot Charts
* XLOOKUP
* Descriptive Statistics
* Trend Analysis
* Forecasting
* Data Visualization
* Business Analysis
* Business Insights
* Data-Driven Decision Making
