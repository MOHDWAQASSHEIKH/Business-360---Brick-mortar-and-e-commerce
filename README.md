# Overview
AtliQ Hardware is experiencing remarkable growth, and to stay ahead in the competitive landscape, they are implementing data analytics using Power BI for the first time. This project aims to provide stakeholders with comprehensive insights across finance, sales, marketing, and supply chain, enabling informed, data-driven decisions. 💼📈

Linkedin: https://tinyurl.com/45j42tkj


![image](https://github.com/user-attachments/assets/39b94c1b-acd0-4828-bad3-9ef1a4333d89)


# Tech Stack
- 🗄️ SQL
- 📊 Power BI Desktop
- 📥 Excel
- 🧮 DAX Language
- ⚙️ DAX Studio (for report optimization)
- 📄 Project Charter File

# Features
- **Finance View**: In-depth financial analysis, covering revenue, expenses, and profit margins. Key KPIs include Net Sales, Gross Margin %, and Net Profit %. Comprehensive P&L Statement with Year-over-Year growth insights. 💰📉
  
- **Sales View**: Insights into product and customer performance, focusing on Customer Performance based on Net Sales and Gross Margin. 🛒📊

- **Marketing View**: Enhanced marketing insights with performance metrics by segment and Net Profit. 📣📈

- **Supply Chain View**: Metrics for optimizing supply chain efficiency. Analyzed the variance between Actual Sales and Forecast accuracy. 🚚📦

- **Executive View**: Critical metrics for top-level decision-makers, showcasing Yearly Trends by Revenue, GM %, NP %, and Market Share %. Lists the TOP 5 Customers & Products by Revenue Contribution. 🏆📊

# Power BI Techniques Learned
- ❓ Key questions to ask before starting a project
- ➕ Creating calculated columns
- ⚙️ Building measures using DAX
- 🗂️ Data modeling
- 📑 Using bookmarks for visual switching
- 📲 Page navigation with buttons
- ⚖️ Using the DIVIDE function to prevent division by zero errors
- 📅 Creating a date table with M language
- 🔄 Dynamic titles based on applied filters
- 📈 Utilizing KPI indicators
- 🎨 Conditional formatting in visuals with icons or background colors
- ✅ Data validation techniques
- ☁️ Power BI services
- 📤 Publishing reports to Power BI services
- 🔄 Setting up a personal gateway for auto-refresh of data
- 📱 Creating Power BI apps
- 🤝 Collaboration, workspace management, and access permissions in Power BI services

# Business Terminology
- 💵 Gross Price
- 📉 Pre-Invoice Deductions
- 📈 Post-Invoice Deductions
- 🧾 Net Invoice Sale
- 📊 Gross Margin
- 💰 Net Sales
- 🤑 Net Profit
- 📊 COGS - Cost of Goods Sold
- 📅 YTD - Year to Date
- 📅 YTG - Year to Go

# Company Background
AtliQ Hardware has expanded rapidly in recent years, operating globally and selling computers and accessories through three main channels:
- 🏪 Retailers
- 🛒 Direct Sales
- 🚚 Distributors

Recently, the company encountered unexpected losses from a new store in America, exacerbated by competitors with robust analytics teams. To thrive in the industry, AtliQ Hardware must build its own analytics team for better data-driven insights and decisions. 🛠️🌍

# Dataset Understanding
A clear understanding of available data is crucial for analysis. Before diving into the analysis, familiarize yourself with the dataset.

## Dimension Table
Contains static data such as customer and product details.

## Fact Table
Contains transactional data.

### gdb041:
- **dim_customer**: 27 distinct markets (e.g., India, USA, Spain), 75 unique customers, 2 platform types (Brick & Mortar and E-commerce).
- **dim_market**: 27 markets, 7 sub-zones, 4 regions (APAC, EU, NAN, LATAM).
- **dim_product**: Divisions and 14 categories (e.g., Internal HDD, keyboard).
- **fact_forecast_monthly**: Forecasts customer needs, aiding in customer satisfaction and cost reduction.
- **fact_sales_monthly**: Similar to forecast table but reflects sold quantities.

### gdb056:
- **freight_cost**: Details travel costs per market with fiscal year.
- **gross_price**: Contains gross price details with product codes.
- **manufacturing_cost**: Manufacturing costs associated with product codes and years.
- **Pre_invoice_deductions**: Pre-invoice deduction percentages per customer.
- **Post_invoice_deductions**: Post-invoice and other deduction details.

# Importing Data into Power BI
Given that the database is MySQL, we will import datasets by providing access credentials.

# Data Model
Data modeling is vital as it forms the foundation of the report. Poor modeling can severely impact performance. In this project, we have adopted the Snowflake data modeling method. ❄️📊

# Key Achievements
- 🎯 Customization: Tailored solutions for AtliQ Hardware.
- 🔗 Data Integration: Seamless integration from Excel, CSV, and MySQL sources.
- 📉 Visualizations: Engaging charts and visuals for enhanced data comprehension.
- ⚡ Performance Optimization: Achieved a 5% increase in report efficiency.

# Data Sources
The dashboard efficiently collects and utilizes data from two primary sources:
- 📊 Excel/CSV Files: Targets, Market Share data, and related info.
- 🗄️ MySQL Database: Facts and dimensions data.
