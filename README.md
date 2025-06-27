
# 📊 D-Mart Sales Analysis | Power BI Project

This repository contains a comprehensive **Power BI dashboard** created for analyzing the sales performance of **D-Mart**, a retail supermarket chain. The report provides interactive insights into sales trends, profit margins, product performance, and regional sales distribution.

---

## 🚀 Features

- 📈 **Sales Trend Analysis** (Monthly & Yearly)
- 🛒 **Top Products & Category Insights**
- 🌍 **Regional and Store-wise Sales Breakdown**
- 💹 **Key KPIs**: Total Sales, Profit, Quantity Sold, Profit Margin
- 🎛️ **Dynamic Slicers**: Date, Region, Store, Category

---

## 🧱 Data Model

The project uses a **star schema** with the following tables:

- **Sales** – Transaction data (Product ID, Date, Quantity, Sales Amount)
- **Product** – Product details (Name, Category, Sub-Category)
- **Store** – Store information (City, Region)
- **Date** – Calendar table (Day, Month, Quarter, Year)

---

## 📐 DAX Measures

- `Total Sales` = SUM(SalesAmount)
- `Total Profit` = SUM(SalesAmount - Cost)
- `Profit Margin (%)` = (Profit / Sales) * 100
- `Average Order Value` = Sales / Orders
- `Quantity Sold` = SUM(Quantity)

---

## 🖼️ Dashboard Pages

1. **Overview** – KPIs and Total Summary
2. **Sales Trend** – Monthly and Yearly trends
3. **Product Performance** – Best-selling and most profitable products
4. **Category Insights** – Comparison of product categories
5. **Regional Analysis** – Store and region-wise performance

---

## ⚙️ Tools & Technologies

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling
- Interactive Data Visualizations

---

## 📂 Repository Structure

```
📁 D-Mart Sales Analysis
│
├── 📄 D-Mart_Sales_Analysis_Report.docx   # Project Report
├── 📊 D_Mart Sales Analysis Project.pbix   # Power BI Dashboard File
└── 📄 README.md                            # Project Overview
```

---

## ✅ Outcome

This dashboard enables business users and decision-makers to monitor D-Mart's sales performance, identify high-performing regions and products, and take data-driven decisions to enhance retail strategy.

---

## 📬 Contact

For queries or collaborations, feel free to connect via [LinkedIn](https://www.linkedin.com) or raise an issue in this repository.
