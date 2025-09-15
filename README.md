# SuperStore-Sales-Dashboard
📊 SuperStore Sales Dashboard – Power BI Project

1️⃣ Project Objective

The purpose of this project is to design and develop an interactive sales dashboard using the Global SuperStore dataset in Power BI.
The dashboard aims to:

  • Provide real-time business insights into sales and profitability.
  
  • Allow stakeholders to explore KPIs dynamically.
  
  • Support strategic decision-making through data-driven visualizations.
  

2️⃣ Dataset Description

➢ Dataset Used: Global SuperStore Dataset (sample business dataset).

➢ Data Size: ~10,000+ rows across multiple years.

➢ Key Fields:

  • Order Date, Ship Date, Sales, Quantity, Discount, Profit, Region, Country, Category, Sub-Category, Segment, Customer Name, Product ID.
  
➢ Data Preparation:

  • Cleaned null values and duplicates using Power Query.
  
  • Standardized date fields for time-series analysis.
  
  • Created calculated columns for profit margin and year-month grouping.
  

3️⃣ Tools & Technologies

• Power BI Desktop – Data modeling and dashboard creation.

• Power Query – Data cleaning and transformation.

• DAX (Data Analysis Expressions) – Custom measures and calculated KPIs.

• Visualization Techniques – Bar charts, Area charts, Donut charts, Pie chart Maps, KPI cards, Filter & Slicers.


4️⃣ Dashboard Features

🔹 Sales & Profit Overview

  ➢ KPI Cards display:
  
    • Total Sales
    • Total Profit
    • Total Orders
    • Ship Days
    
  ➢ Year-over-Year comparison with trend indicators.
  
🔹 Regional Analysis

  ➢ Map Visualization to display sales and profit by country/region.
  
  ➢ Heatmap-style shading to highlight high vs. low-performing areas.
  
🔹 Category & Sub-Category Insights

  ➢ Stacked Bar Charts showing contribution of categories to total sales.
  
  ➢ Drill-down into sub-categories to identify profit-driving vs. loss-making products.
  
🔹 Customer & Segment Analysis

  ➢ Breakdown of sales by customer segments (Consumer, Corporate, Home Office).
  
  ➢ Top 10 Customers contributing highest sales.
  
🔹 Time-Series Trends

  ➢ Area Chart showing monthly and yearly performance of sales and profit.
  
  ➢ Seasonal fluctuations clearly highlighted.
  
🔹 Interactive Slicers & Filters

  ➢ Slicers for: 
  
    • Region
    • Category
    • Year
    
  ➢ Enables customized analysis for stakeholders.
  

5️⃣ Key Insights from Dashboard

📌 Profitability varies greatly by sub-category – some generate high sales but low or negative profit.

📌 Regional imbalance – some countries outperform while others incur losses.

📌 Discounts affect profitability – higher discounts often lead to reduced profit margins.

📌 Consumer Segment dominates sales, but corporate clients show better profit margins.

📌 Seasonality observed – higher sales during certain months (festive season).


6️⃣ Project Workflow

  1. Data Import.
    • Loaded Global SuperStore dataset into Power BI.
  2. Data Cleaning (Power Query)
    • Removed null/duplicate records.
    • Standardized column names.
    • Created date hierarchies.
  3. Data Modeling
    • Built relationships between tables (Orders, Returns, People).
    • Created measures using DAX for KPIs.
  4. Visualization
    • Designed reports using a mix of bar charts, line graphs, maps, and KPI cards.
    • Added slicers for interactive filtering.
  5. Dashboard Publishing
    • Saved as .pbit (Power BI Template) for easy reuse.


7️⃣ Folder Structure (For GitHub Repo)

📂 SuperStore-Sales-Dashboard

 ├── 📄 SuperStore Sales Dashboard.pbit   # Power BI Template
 
 ├── 📂 Dataset/                          # (Optional: store sample dataset here)
 
 ├── 📂 Screenshots/                      # Dashboard preview images
 
 ├── 📄 README.md                         # Documentation


8️⃣ How to Use This Project

  1.Clone or download this repository.
  
  2.Open SuperStore Sales Dashboard.pbit in Power BI Desktop.
  
  3.Load the Global SuperStore dataset when prompted.
  
  4.Explore the dashboard and apply slicers for insights.
  

9️⃣ Future Enhancements

• Integration with live SQL/Excel/CSV data sources.

• Implement AI & ML-driven forecasting (Power BI AI features).

• Add What-if analysis for sales planning.

• Advanced KPIs: Customer Lifetime Value (CLV), Churn Prediction.


🔟 Project Outcomes

✅ Gained hands-on experience in Power BI visualization & dashboarding.

✅ Improved skills in data cleaning, DAX calculations, and interactive reporting.

✅ Produced a professional BI dashboard suitable for portfolio and business use.
