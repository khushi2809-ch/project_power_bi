# 📊 Retail Sales Dashboard (Power BI)

## 📌 Project Overview

This project is an interactive **Retail Sales Dashboard** built using **Power BI**. It provides insights into sales performance, customer behavior, product performance, and business trends through interactive visualizations.

## 🎯 Objectives
- Analyze overall sales performance.
- Identify top-selling products.
- Monitor monthly sales trends.
- Compare sales across different categories and states.
- Analyze customer purchasing behavior.
- Track payment methods and delivery status.

## 🛠️ Tools & Technologies
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
  
📂 Dataset
The dataset contains retail sales transaction data with the following fields:
- Order ID
- Order Date
- Customer Name
- Product
- Category
- Quantity
- Unit Price
- Total Sales
- City
- State
- Payment Method
- Delivery Status
- Rating

## 🧹 Data Cleaning
Data cleaning was performed in **Power Query**:
- Removed duplicate records
- Changed data types
- Handled invalid values
- Trimmed extra spaces
- Handled missing values
- Created dimension tables
- Built a Star Schema data model

## 📐 Data Model
The project follows the **Star Schema** model.
### Fact Table
- fact_table
### Dimension Tables
- dim_date
- dim_product
- dim_customer

📊 Dashboard Features

📄 Page 1 – Executive Dashboard
- Total Sales KPI
- Total Orders KPI
- Total Customers KPI
- Average Sales
- Average Rating
- Sales Trend by Month
- Sales by Category
- Sales by State
- Payment Method Analysis
- Interactive Slicers

📄 Page 2 – Detailed Analysis
- Top 10 Products by Sales
- Sales by City
- Delivery Status Analysis
- Quantity Sold by Product
- Customer Details Table

📈 DAX Measures
Total Sales = SUM(fact_table[Total_Sales])
Total Orders = COUNT(fact_table[Order_ID])
Total Quantity = SUM(fact_table[Quantity])
Average Sales = AVERAGE(fact_table[Total_Sales])
Average Rating = AVERAGE(fact_table[Rating])
Total Customers = DISTINCTCOUNT(dim_customer[Customer_Name])

## 💡 Key Insights
- Identified the best-selling products.
- Compared sales across different product categories.
- Analyzed monthly sales trends.
- Identified high-performing states.
- Evaluated customer payment preferences.
- Tracked delivery performance.

## 🚀 Skills Demonstrated
- Data Cleaning
- Data Modeling
- Star Schema
- Power Query
- DAX
- Dashboard Design
- Business Intelligence
- Data Visualization

## 📁 Project Structure
Retail-Sales-Dashboard/
│
├── Dataset/
│   └── Retail_Sales_Dataset.xlsx
│
├── Dashboard/
│   └── Retail_Sales_Dashboard.pbix
│
├── Images/
│   ├── Dashboard_Page1.png
│   ├── Dashboard_Page2.png
│   └── Data_Model.png
│
└── README.md

## 👩‍💻 Author

**Khushi Chaudhary**

Aspiring Data Analyst | Power BI | SQL | Excel | Python

