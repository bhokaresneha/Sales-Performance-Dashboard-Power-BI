
## 📌 Project Overview
This project presents an interactive **Sales Performance Dashboard** built in **Microsoft Power BI** to analyze sales data for a global Electronics & Furniture company.

The dashboard provides key business insights into sales, profit, product performance, regional distribution, salesperson performance, and monthly sales trends, enabling management to make data-driven decisions.


---

## 📸 Dashboard Preview

<img width="1468" height="859" alt="Screenshot 2026-07-06 110253" src="https://github.com/user-attachments/assets/2c61c686-06dd-46e3-8eff-8a40ab429ba4" />


---

# 🎯 Business Problem

The management team wanted answers to the following questions:

- How much total revenue and profit has the company generated?
- Which category generates more revenue?
- Which regions contribute the highest sales?
- Who are the top-performing salespeople?
- What are the monthly sales trends?
- Which countries generate the highest profit margin?

---

# 🛠 Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- Data Modeling

---

# 📂 Dataset Information

The dataset contains sales transactions from **January 2024 to September 2024**.

### Main Fields

- Order Date
- Region
- Country
- Category
- Product
- Salesperson
- Quantity
- Unit Price
- Total Sales
- Profit

---

# 📈 Dashboard Features

## KPI Cards

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Quantity Sold
- 📊 Profit Margin %

---

## Visualizations

### 📅 Monthly Sales Trend
Shows sales performance over time.

### 📦 Sales by Category
Compare Electronics vs Furniture sales.

### 🌍 Sales Distribution by Region
Donut chart showing regional sales contribution.

### 👨‍💼 Sales Performance by Salesperson
Ranks salespeople based on total sales.

### 🌎 Country-wise Performance
Displays

- Country
- Total Sales
- Total Profit
- Profit Margin %

### 🎛 Interactive Slicers

- Region
- Salesperson
- Category

---

# 📊 DAX Measures

```DAX
Total Sales = SUM(Sales_Data[TotalSales])

Total Profit = SUM(Sales_Data[Profit])

Total Quantity Sold = SUM(Sales_Data[Quantity])

Total Orders = COUNTROWS(Sales_Data)

Average Order Value =
DIVIDE([Total Sales],[Total Orders])

Profit Margin % =
DIVIDE([Total Profit],[Total Sales],0)*100
```

---

# 📌 Key Insights

### 💰 Overall Performance

- Total Sales: **₹137K**
- Total Profit: **₹24K**
- Total Quantity Sold: **317**
- Overall Profit Margin: **18%**

---

### 📦 Category Analysis

- Electronics generated significantly higher revenue than Furniture.
- Electronics is the company's best-performing category.

---

### 🌍 Regional Analysis

- Asia contributes the highest sales (~38%).
- North America follows closely.
- Europe contributes the smallest share.

---

### 👨‍💼 Salesperson Performance

- Charlie is the highest-performing salesperson.
- Alice ranks second.

---

### 📈 Monthly Trend

- Sales fluctuate throughout the year.
- Highest sales were recorded during the later months of the period, indicating seasonal growth.

---

### 🌎 Country Performance

The dashboard provides country-wise comparison of:

- Total Sales
- Total Profit
- Profit Margin %

to identify high-performing markets.

---

# 📋 Business Questions Answered

✔ Total Sales & Profit

✔ Best Performing Category

✔ Highest Revenue Region

✔ Best Salesperson

✔ Monthly Sales Trend

✔ Profit Margin %

✔ Country-wise Performance

✔ Regional Sales Distribution

✔ Product Category Comparison

✔ Interactive Filtering

---

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Power Query
- Data Modeling
- DAX Calculations
- KPI Design
- Dashboard Design
- Data Visualization
- Business Analysis
- Interactive Reporting

---

# ⭐ Dashboard Highlights

- Modern executive dashboard design
- Interactive slicers
- Professional KPI cards
- Business-focused insights
- Clean and responsive layout
- Easy-to-understand visualizations

---

## 👩‍💻 Author

**Sneha Bhokare**

Aspiring Data Analyst | Power BI | SQL | Excel | Python

GitHub:https://github.com/bhokaresneha/Sales-Performance-Dashboard-Power-BI

LinkedIn: https://www.linkedin.com/in/sneha-bhokare-891488224/

---

## ⭐ If you found this project helpful, consider giving it a Star!
