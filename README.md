# Spend & Savings Dashboard

**Visualizing spend and savings patterns to optimize budgets and identify cost-saving opportunities.**

---

## 📋 Project Overview
This project demonstrates end-to-end business intelligence and data analytics capabilities. The Spend & Savings Dashboard analyzes organizational spend data to highlight trends, identify savings opportunities, and support data-driven decision-making. Built with Power BI and DAX, this dashboard showcases data modeling, visualization, and analytical skills in a real-world context.

---

## 📌 Business Context
The dashboard helps stakeholders answer critical business questions:

- How has spending evolved over time?  
- Which products or categories offer potential savings?  
- Are we staying within target spends and KPI goals?
- What are the geographic spend patterns?

---

## 📊 Data Overview
- **Data Source:** Anonymized spend and transaction data.  
- **Fields Included:** Date, GEO, Category, Product, Spend, Savings, KPI.  
- **Data Model:** Star schema with one fact table (`Fact_Spend`) and three dimension tables (`Dim_Date`, `Dim_Product`, `Dim_Geo`).  

**Actual Spend Sample:** [data_sample/spend_data_sample.csv](data_sample/spend_data_sample.csv)  
**Target Sample:** [data_sample/target_data_sample.csv](data_sample/target_data_sample.csv)

---

## 🛠️ Technical Stack
- **Power BI:** Dashboard creation and visualization    
- **DAX:** Advanced calculations and measures  
- **Data Modeling:** Star schema design for efficient reporting

---

## 🌟 Key Features
- **Real-time Spend Tracking** – Monitor actual vs target spend across geographies and product lines
- **Automated Savings Identification** – DAX-powered calculations to identify cost-saving opportunities
- **Interactive Filtering** – Dynamic dashboard filters for budget variance analysis by category, product, and geography
- **Time-based Analysis** – Year-over-year and month-over-month spend trend analysis
- **KPI Monitoring** – Track savings as a percentage of spend against organizational targets

---

## 🔑 Key Measures & Metrics
Core metrics included in the dashboard:

| Metric | Description |
|--------|-------------|
| **Total Spend** | Sum of all spend amounts |
| **Total Savings** | Sum of all savings amounts |
| **KPI %** | (Savings ÷ Spend) × 100 |
| **Spend by Category/Product** | Aggregated spend trends by dimension |
| **Target vs Actual** | Budget variance analysis |

---

## 📈 Key Insights
- Visualized total spend trends over time to detect high-spending periods and seasonal patterns.  
- Identified top categories and products with highest cost-saving potential.  
- Compared target vs actual spend to monitor budget adherence and variance.
- Analyzed geographic spend distribution to identify regional spending patterns.

---

## 🖼️ Dashboard Screenshots
View the dashboard visualizations in the `screenshots/` folder:
- **Main Dashboard:** Pie Chart for spend and savings trends, card visuals for key metrics, tables for actual spend data
- **KPI Comparison:** Line chart comparing target vs actual KPI with variance indicators
- **Revenue & Profit Margin:** Line and column combination chart showing revenue trends and profit margin by year
- **Customer Satisfaction:** Line, Clustered/Stacked columns and Pie chart for overall satisfaction score
- **Interactive Elements:** Slicers for filtering by Category, Product, Geo, and Year
- **Star Schema Diagram** – Visual representation of the data model

---

## ✅ Prerequisites
Before reproducing this project, ensure you have:
- **Power BI Desktop** (version 2020.12 or later)
- Basic understanding of star schemas and dimensional modeling
- Familiarity with DAX formulas (recommended)

---

## 🗂️ Repository Structure
