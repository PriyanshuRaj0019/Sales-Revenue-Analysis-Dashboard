# Sales & Revenue Analysis Dashboard

## Overview

The Sales & Revenue Analysis Dashboard is an interactive Business Intelligence project developed using Python and Microsoft Power BI. The project focuses on analyzing sales performance, monitoring key business metrics, identifying top-performing products, and generating actionable business insights through data visualization.

The dashboard enables users to explore sales data interactively using filters and slicers, helping stakeholders make informed business decisions.

---

## Project Objectives

* Analyze sales performance using historical sales data.
* Track key business KPIs.
* Monitor sales trends over time.
* Identify top-performing products.
* Compare sales performance across regions and categories.
* Generate business insights through interactive visualizations.

---

## Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
* Microsoft Power BI
* CSV Dataset
* GitHub

---

## Dataset Information

The dataset contains retail sales transaction records with the following attributes:

* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Customer Name
* Segment
* Country
* City
* State
* Postal Code
* Region
* Product ID
* Category
* Sub-Category
* Product Name
* Sales

---

## Data Processing

The dataset was cleaned and prepared using Python and Pandas.

### Data Preparation Steps

* Loaded dataset from CSV file.
* Checked for missing values.
* Checked for duplicate records.
* Converted date columns into datetime format.
* Created additional time-based features:

  * Year
  * Month
  * Month Name
  * Quarter
* Exported cleaned dataset for Power BI visualization.

---

## Key Performance Indicators (KPIs)

The dashboard tracks the following KPIs:

### Total Sales

Measures overall revenue generated from all sales transactions.

### Total Orders

Measures the total number of unique customer orders.

### Total Customers

Measures the number of unique customers.

---

## Dashboard Features

### Sales Trend Analysis

Visualizes monthly sales performance to identify growth patterns and seasonal trends.

### Regional Sales Analysis

Compares sales performance across different regions.

### Category Analysis

Analyzes revenue contribution by product category.

### Top Products Analysis

Identifies the highest revenue-generating products.

### Interactive Filtering

Provides dynamic filtering through:

* Region
* Category
* Year

---

## Dashboard Preview


<img width="1415" height="796" alt="image" src="https://github.com/user-attachments/assets/9ccbe851-ec51-48d6-a9a7-2b0746d30354" />


## Business Insights

* West region generated the highest sales revenue.
* Technology category contributed the largest share of total sales.
* Sales showed an overall increasing trend during the analysis period.
* A small group of top-performing products contributed significantly to overall revenue.
* Sales performance varied across regions and product categories.
* Interactive filtering enabled detailed analysis and business exploration.

---

## Project Structure

```text
sales-revenue-analysis-dashboard/
│   └── cleaned_sales_data.csv
│   └── sales_analysis.ipynb
│   └── Sales_Dashboard.pbix
│   └── dashboard_overview.png
├── README.md
```

## Learning Outcomes

Through this project, the following skills were developed:

* Data Cleaning and Preparation
* Exploratory Data Analysis (EDA)
* KPI Development
* Business Intelligence Reporting
* Power BI Dashboard Design
* Data Visualization
* Business Insight Generation
* GitHub Project Documentation

---

## Future Enhancements

* Profitability Analysis
* Customer Segmentation
* Forecasting and Trend Prediction
* Automated Data Refresh
* Advanced Power BI DAX Measures

---

## Author

**Priyanshu Raj**

Data Analytics | Machine Learning | Generative AI | Agentic AI
