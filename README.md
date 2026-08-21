# 📊 Flipkart E-Commerce Sales Dashboard (Power BI)

## 🚀 Project Overview

This project presents an interactive Power BI dashboard built using Flipkart E-Commerce Sales data. The dashboard provides meaningful insights into sales performance, customer behavior, product performance, and regional revenue using Power BI visualizations, DAX measures, and Power Query.

---

## 🎯 Objectives

- Analyze overall business performance.
- Track revenue and order trends.
- Understand customer purchasing behavior.
- Identify high-performing product categories.
- Compare revenue across different zones.
- Build an interactive business dashboard.

---

## 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel / CSV

---

## 📂 Dataset Information

The dataset contains the following information:

- Order Date
- Delivery Date
- Customer ID
- Customer Age
- Customer Gender
- Product Category
- Sub Category
- Product Name
- Unit Price
- Sale Price
- Shipping Fee
- Order Quantity
- Delivery Type
- Order Status
- Rating
- Zone
- Location

---

## 📈 Dashboard Features

### KPI Cards
- 💰 Total Revenue
- 📦 Total Products Sold
- 👥 Total Customers
- 🛒 Total Orders
- ⭐ Average Rating

### Filters (Slicers)
- Year
- Month
- Week Type
- Product Category
- Rating

### Visualizations
- Revenue by Year
- Revenue by Zone
- Products Sold by Year
- Orders by Year

---

## 📊 DAX Measures Used

```DAX
Total Revenue = SUM(ECommerceSales[SalePrice])

Total Products Sold = SUM(ECommerceSales[OrderQuantity])

Total Customers = DISTINCTCOUNT(ECommerceSales[CustomerID])

Total Orders = DISTINCTCOUNT(ECommerceSales[OrderID])

Average Rating = AVERAGE(ECommerceSales[Rating])
```
---

## 📁 Project Structure

```
Flipkart-PowerBI-Dashboard
│
├── Flipkart Dashboard.pbix
├── EcommerceSales.csv
├── README.md
└── dashboard.png
```

---

## 📌 Key Insights

- Revenue increased significantly in recent years.
- Zone 3 generated the highest revenue.
- Product sales showed steady growth.
- Customer orders increased year by year.
- Dashboard supports interactive filtering for deeper analysis.

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. If prompted, reconnect the dataset.
4. Refresh the report.
5. Explore the dashboard using the available filters.

---

## 👨‍💻 Author

**Kundasi Jaswitha**
