# 🎁 Ferns N Petals (FnP) Sales Analysis

## 📌 Project Overview
[cite_start]This project analyzes a dataset from FNP (Ferns and Petals), an e-commerce platform specializing in sending gifts for various occasions[cite: 2]. [cite_start]The goal is to uncover key insights related to sales trends, customer behavior, and product performance [cite: 4] by taking raw data through a complete ETL pipeline and building an interactive Excel dashboard.

## 🗂️ Dataset Details
[cite_start]The dataset contains details about the products, orders, customers, and relevant dates[cite: 3].
* **customers.csv:** Contains 100 customer records.
* **orders.csv:** Contains 1,000 transaction records.
* **products.csv:** Contains 70 unique products.

## 🎯 Business Objectives
[cite_start]The project answers several key business questions to help the company improve its sales strategy and optimize customer satisfaction[cite: 5]:
* [cite_start]**Total Revenue:** Identify the overall revenue[cite: 6].
* [cite_start]**Average Order and Delivery Time:** Evaluate the time taken for orders to be delivered[cite: 7].
* [cite_start]**Monthly Sales Performance:** Examine how sales fluctuate across the months of 2023[cite: 8].
* [cite_start]**Order Quantity vs. Delivery Time:** Analyze if higher order quantities impact delivery times[cite: 14].

## ⚙️ Tools & ETL Workflow
* **Extract & Transform (Power Query):** Cleaned missing values, removed irrelevant text, standardized phone numbers/dates, and calculated derived metrics like "Delivery Delay" and "Revenue".
* **Data Modeling (Power Pivot):** Designed a robust Star Schema connecting dimension tables (Customers, Products) to the central fact table (Orders).
* **Visualization (Excel PivotTables):** Built dynamic dashboards using Slicers for temporal and categorical filtering (e.g., filtering by Occasion).

## 📊 Key Insights
* **Revenue & AOV:** Achieved a Total Revenue of **$3.52M** with an Average Order Value (AOV) of **$3,520**.
* **Logistics Efficiency:** The average delivery time stands at **5.53 days**. Correlation analysis (~0.003) indicates that higher order volumes do not negatively impact delivery speed.
* **Seasonality:** Revenue peaks significantly in August, heavily driven by the Raksha Bandhan festival.

## 🖼️ Dashboard Previews

### Main Dashboard
![Main Dashboard](Dashboard/Screenshots/Main_Dashboard.jpg)

### Sales Dashboard
![Sales Dashboard](Dashboard/Screenshots/Sales_Dashboard.jpg)

### Operations Dashboard
![Operations Dashboard](Dashboard/Screenshots/Operations_Dashboard.jpg)

## 🚀 How to Run This Project
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YourUsername/FnP-Sales-Analysis.git](https://github.com/YourUsername/FnP-Sales-Analysis.git)
