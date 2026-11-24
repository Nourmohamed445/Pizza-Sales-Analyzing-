# Pizza-Sales-Analyzing-
# 🍕 Pizza Sales Analysis

## 📌 Project Overview
An end-to-end data analysis project focused on transactional sales data from a pizza store (`pizza_sales.csv`). The objective is to extract actionable business insights, track key performance indicators (KPIs), and analyze sales trends to support management decisions in marketing, menu optimization, inventory, and operations.

## 🎯 Business Objectives & Key Questions Answered
This analysis addresses core business questions, including:
- What are the **Total Revenue**, **Total Pizzas Sold**, and **Total Orders**?
- What are the **Average Order Value (AOV)** and **Average Pizzas per Order**?
- How do sales perform across **pizza categories** (Classic, Supreme, Veggie, Chicken) and **sizes** (S, M, L, XL)?
- Which pizzas are the **Top 5 best-sellers** and **Bottom 5 least-sellers**?
- What are the **daily, hourly, and monthly** sales trends (including peak hours/seasons and ingredient/inventory needs)?

## 📊 Key Performance Indicators (KPIs)
- **Total Revenue:** `817,860.05 `
- **Total Pizzas Sold:** `49,574`
- **Total Orders:** `21,350`
- **Average Order Value (AOV):** `38.31`
- **Average Pizzas per Order:** `2.32`

## 🗂️ Dataset Overview (`pizza_sales.csv`)
- `order_id`: Unique identifier for each order
- `pizza_id`: Unique identifier for each pizza
- `pizza_name`: Name of the pizza sold
- `quantity`: Number of pizzas sold per order
- `total_price`: Total revenue per transaction
- `date` & `time`: Order timestamp for time-series analysis
- `pizza_category` & `pizza_size`: Product classification attributes

## 📈 Analysis & Visualizations
- **Time-Based Trends:** Daily, hourly, and monthly patterns to guide staffing, rush-hour prep, and seasonal promotions.
- **Category & Size Breakdown:** Revenue and quantity share by category and size (e.g., Classic dominance, Large size revenue contribution).
- **Top & Bottom Performers:** Identifying best-selling items for promotion and underperforming items for menu review or removal.
- **Ingredient & Inventory Insights:** Supporting stock planning for high-demand items and categories.

## 💡 Key Recommendations for Management
- **Marketing & Promotions:** Focus campaigns on top-performing categories, best-selling pizzas, and peak periods (such as summer promotions).
- **Menu Optimization:** Evaluate low-performing pizzas for recipe tweaks, bundling, or removal.
- **Operations & Staffing:** Align shift schedules and ingredient stock levels with hourly, daily, and monthly demand peaks.
- **Ongoing Tracking:** Monitor core KPIs regularly via dashboards for continuous improvement.

## 🛠️ Tools & Deliverables
- **Language & Analysis:** Python, Jupyter Notebook *( Pandas - Matplotlib )*
- **Documentation:** Business Requirements Document (BRD)
- **Data Exploration:** Charts & dashboards *( Matplotlib )*

## 📁 Repository Structure
```text
├── data/
│   └── pizza_sales.csv
├── notebooks/
│   └── pizza_sales_analysis.ipynb
├── docs/
│   └── Business Requirements Document.docx
├── images/ # (اختياري) صور الرسوم البيانية والداشبورد
└── README.md
