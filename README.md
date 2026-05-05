# Ferns N Petals Sales Analysis Dashboard

## Project Overview
This project analyzes sales and operational performance for **Ferns N Petals (FnP)** using Excel.

The workflow covered the full analytics lifecycle:

- Data Cleaning
- Data Transformation using Power Query
- Star Schema Data Modeling using Power Pivot
- KPI Analysis with Pivot Tables
- Interactive Dashboard Development

The final output is an interactive **3-page Excel dashboard** built for business decision-making.

---

## Dataset
The project is built using 3 datasets:

| File | Description |
|---|---|
| customers.csv | Customer information |
| orders.csv | Sales transactions |
| products.csv | Product details |

### Dataset Summary
- **100 Customers**
- **1,000 Orders**
- **70 Products**

---

## Data Model

A **Star Schema** was implemented for efficient analysis.

### Fact Table
- Orders

### Dimension Tables
- Customers
- Products

Power Pivot relationships were used to connect dimension tables with the central fact table.

## Data Model Preview
![Data Model](images/data-model.png)

---

## Dashboard Structure

The dashboard consists of 3 interactive pages with slicers and filters for dynamic analysis.

### 1. Main Dashboard
Provides a high-level overview of business performance and key KPIs.

Includes:
- Total Revenue
- Average Order Value (AOV)
- Average Delivery Time
- Total Customers
- Monthly Revenue Trend
- Top Market Analysis
- Top 5 Products
- Gender Distribution Analysis

Interactive Filters:
- Occasion Slicer
- Order Date (Month) Slicer

#### Preview
![Main Dashboard](images/main-dashboard.png)

---

### 2. Sales Dashboard
Focused on analyzing revenue performance and customer purchasing behavior.

Includes:
- Occasion-wise sales analysis
- Product performance analysis
- Customer insights
- Market performance breakdown

Interactive Features:
- Occasion-based filtering
- Time-based sales filtering

#### Preview
![Sales Dashboard](images/sales-dashboard.png)

---

### 3. Operations Dashboard
Focused on monitoring operational efficiency and delivery performance.

Includes:
- Orders volume vs Delivery time 
- Average delivery metrics
- Delivery by city
- Revenue by hours

Interactive Features:
- Operational filtering by occasion and date
- Delivery performance monitoring

#### Preview
![Operations Dashboard](images/operations-dashboard.png)
---

## Key KPIs

| KPI | Value |
|---|---|
| Total Revenue | ₹35.2L |
| Average Order Value | ₹3,520 |
| Average Delivery Time | 5.53 Days |

---

## Key Insights
- Revenue peaks significantly in **August** during **Raksha Bandhan**
- Festival seasons strongly impact customer purchasing behavior
- **Soft Toys** and **Magnam Sets** are top-performing products
- Order quantity has minimal effect on delivery speed (**Correlation ≈ 0.05**)

---

## Tools Used
- Microsoft Excel
- Power Query
- Power Pivot
- Pivot Tables
- Dashboard Design

---

## Project Folder Structure

```bash
FnP-Sales-Analysis/
│
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
│
├── FnP_Sales_Analysis.xlsx
│
├── images/
│   ├── data-model.png
│   ├── main-dashboard.png
│   ├── sales-dashboard.png
│   └── operations-dashboard.png
│
└── README.md
```

---

## Business Recommendations
- Optimize inventory before peak festival seasons
- Prioritize top-performing products before high-demand months
- Closely monitor delivery efficiency during seasonal spikes

---

## 📬 Contact

📧 Email: [mahmoud23456123@gmail.com](mailto:mahmoud23456123@gmail.com)
🔗 LinkedIn: [https://www.linkedin.com/in/mahmoudgamalsaad](https://www.linkedin.com/in/mahmoudgamalsaad)
