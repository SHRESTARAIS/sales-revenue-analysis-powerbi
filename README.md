# 📊 Sales & Revenue Analysis Dashboard

## 📌 Project Overview

This project is an interactive **Sales & Revenue Analysis Dashboard** built using **Microsoft Power BI**.

The dashboard analyzes sales data to identify sales trends, top-performing categories, regions, and products. It also provides interactive filters and KPIs to support business analysis and decision-making.

## 🎯 Project Objectives

* Analyze overall sales performance

* Track sales trends over time

* Identify the highest-performing product categories

* Compare sales performance across regions

* Identify top-performing products

* Provide interactive filtering using slicers

* Generate meaningful business insights from sales data

## 🛠️ Tools & Technologies

* **Microsoft Power BI Desktop**

* **Power Query**

* **DAX**

* **CSV Dataset**

* **GitHub**

## 📂 Dataset

The project uses a **Superstore Sales Dataset** containing information such as:

* Order Date

* Ship Date

* Order ID

* Customer ID

* Customer Name

* Category

* Sub-Category

* Product Name

* Region

* State

* City

* Sales

The dataset was imported into Power BI using a CSV file.

## 🧹 Data Preparation

The dataset was prepared using **Power Query**.

The following checks were performed:

* Checked column quality

* Verified data types

* Confirmed there were no errors

* Confirmed there were no empty values

* Converted date columns to appropriate date types

* Verified numerical and text fields

## 📊 Dashboard Features

### Key Performance Indicators

* **Total Sales:** 2.26M

* **Total Orders:** 5K

* **Total Customers:** 793

### Visualizations

* Monthly Sales Trend

* Sales by Category

* Sales by Region

* Top 10 Products by Sales

### Interactive Filters

* Category slicer

* Region slicer

* Order Date slicer

## 💡 Key Business Insights

1. **Technology is the highest-selling product category.**

2. **The West region generates the highest sales, with total sales of 710.22K.**

3. **Canon imageCLASS 2200 Advanced Copier is the top-performing product by total sales, generating 61,599.82 in sales.**

4. **November has the highest monthly sales in the analyzed dataset.**

## 📈 DAX Measures

### Total Sales


Total Sales = SUM(Sales\[Sales])

### Total Orders


Total Orders = DISTINCTCOUNT(Sales\[Order ID])

### Total Customers


Total Customers = DISTINCTCOUNT(Sales\[Customer ID])

## 📸 Dashboard Preview

The Power BI dashboard provides an interactive view of sales performance using KPIs, charts, and slicers.

![Sales Revenue Dashboard](./Screenshot/Sales_Revenue_Dashboard.png)

## 📁 Project Structure


Sales-Revenue-Analysis

│

├── Dataset

│   └── train.csv

│

├── PowerBI

│   └── Sales\_Revenue\_Analysis\_Dashboard.pbix

│

├── Screenshot

│   └── Sales\_Revenue\_Dashboard.png

│

└── README.md

## 🚀 Learning Outcomes

Through this project, I practiced:

* Data import and preparation

* Power Query

* DAX measures

* KPI creation

* Data visualization

* Interactive slicers

* Business insight generation

* Dashboard design

* GitHub project documentation

## 👩‍💻 Author

**Shresta Rai S.**

Computer Science & Engineering

K.V.G. College of Engineering
