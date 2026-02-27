📊 Sales & Revenue Dashboard – Business Intelligence Project
📌 Project Overview

Developed an interactive Sales & Revenue Dashboard using the US Superstore dataset (2014–2017) to analyze business performance across revenue, profit, customer segments, product categories, and regions.
This project demonstrates advanced skills in Data Modeling, DAX, KPI Development, and Business Intelligence reporting.

🏗 Data Modeling
  
    - Designed a structured data model following Star Schema principles
    - Established relationships between:
      - Fact Table (Sales Transactions)
      - Dimension Tables (Date, Customer, Product, Region)
    - Optimized data relationships to improve report performance

🔄 Data Transformation (Power Query / ETL)
  
  - Cleaned and standardized raw sales data
  - Removed duplicates and handled missing values
  - Created calculated columns for:
    - Profit Margin
    - Year & Month extraction
    - Category groupings
  - Performed data type corrections and normalization

🧮 DAX Measures Implemented
  
  - Total Revenue = SUM(Sales[Sales])
  - Total Profit = SUM(Sales[Profit])
  - Total Orders = DISTINCTCOUNT(Sales[Order ID])
  - Profit Margin % = DIVIDE([Total Profit], [Total Revenue])
  - Year-over-Year Growth %
  - Dynamic KPI calculations using filter context

📈 Dashboard Features
  
  - KPI Cards (Revenue, Profit, Orders, Margin, Customers)
  - Monthly Revenue & Profit Trend Analysis
  - Category vs Profit Comparison
  - Regional Sales Performance
  - Sub-Category Profitability Analysis
  - Segment-wise Revenue Distribution
  - Interactive Slicers (Year, Category, Segment, Region, Ship Mode)

📊 Dataset Details
  
  - 9,994 Transactions
  - 793 Customers
  - 4 Regions
  - 49 States
  - Time Period: 2014–2017

🎯 Key Business Insights

  - Identified high-performing product categories and regions
  - Detected loss-making sub-categories
  - Analyzed customer contribution to total revenue
  - Measured annual growth trends and profitability

💡 Skills Demonstrated

Data Modeling | DAX | Power Query | ETL | KPI Reporting | Business Intelligence | Dashboard Design | Data Visualization | Analytical Thinking

🚀 Project Objective

To transform raw transactional data into an interactive and insight-driven dashboard that supports data-driven business decisions and performance monitoring.
