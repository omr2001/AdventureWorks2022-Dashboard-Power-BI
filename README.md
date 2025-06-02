# 🚴 AdventureWorks 2022 Sales & Performance Dashboard

## 📊 Project Overview

This project utilizes the **AdventureWorks 2022** sample database to build an interactive **Business Intelligence (BI) dashboard**. The goal is to analyze key performance indicators (KPIs) such as sales revenue, product performance, regional trends, and customer demographics, using a star schema model and visual storytelling.

---

## 🎯 Objectives

- 🔍 Explore and clean AdventureWorks 2022 relational data.
- 🧱 Design a star schema for efficient querying and reporting.
- 📈 Create an interactive Power BI dashboard highlighting business performance.
- 📊 Enable decision-makers to quickly interpret and act on data insights.

---

## 🧰 Tools & Technologies

- **Database**: Microsoft SQL Server, AdventureWorks2022 sample database
- **ETL & Modeling**: SQL Server Management Studio (SSMS), Power Query
- **Data Visualization**: Power BI
- **Schema Design**: Star Schema (Fact & Dimension tables)
- **DAX**: For calculated columns, KPIs, and time intelligence

---

## 📁 Data Model

The dashboard is based on a **star schema** with:

### 🌟 Fact Table:
- `FactInternetSales`: sales data, quantity, unit price, order date, etc.

### 🧭 Dimension Tables:
- `DimCustomer`: customer demographics  
- `DimProduct`: product name, category, subcategory  
- `DimSalesTerritory`: geography data  
- `DimDate`: time intelligence  
- `DimReseller` (if included): reseller channel insights  

---

## 📊 Key Dashboard Features

### 🧮 KPIs:
- Total Sales Revenue  
- Gross Profit Margin  
- Average Sales per Customer  
- Product Return Rate  

### 🌍 Visuals:
- **Sales by Region** (Map)  
- **Top Products by Revenue** (Bar chart)  
- **Sales Trend Over Time** (Line chart)  
- **Customer Segment Distribution** (Pie chart)  
- **Sales by Category/Subcategory** (Treemap or Matrix)

### ⏱ Time Intelligence:
- Year-over-Year growth  
- Monthly sales comparison  
- Filter by year, quarter, month

---

## 📈 Business Insights

- The majority of revenue comes from [e.g., North American territory or specific product line].
- Sales peak during [e.g., Q4 or holiday season] across most regions.
- [e.g., Mountain Bikes] consistently outperform other product categories.
- Key customer segments contribute disproportionately to total revenue.
