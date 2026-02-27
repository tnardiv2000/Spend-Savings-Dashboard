# Spend & Savings Dashboard

**Visualizing spend and savings patterns to optimize budgets and identify cost-saving opportunities.**

---

## 📌 Business Context
This project analyzes organizational spend data to highlight trends, identify savings opportunities, and support data-driven decision-making. The dashboard helps answer questions like:

- How has spending evolved over time?  
- Which products or categories offer potential savings?  
- Are we staying within target spends?

---

## 📊 Data Overview
- **Data Source:** Anonymized spend and transaction data.  
- **Fields Included:** Date, GEO, Category, Product, Spend, Savings, KPI.  
- **Data Model:** Star schema with one fact table (`Fact_Spend`) and four dimension tables (`Dim_Date`, `Dim_Product`, `Dim_Geo`).  

**Actual Spend Sample:** [data_sample/spend_data_sample.csv](data_sample/spend_data_sample.csv)  
**Target Sample:** [data_sample/target_data_sample.csv](data_sample/target_data_sample.csv)
---

## 🛠️ Technical Stack
- **Power BI:** Dashboard creation and visualization    
- **SQL:** Data extraction and transformation  
- **Data Modeling:** Star schema design for efficient reporting

---

## 🔑 Key Measures & Metrics
Some of the key metrics included in the dashboard:

| Metric | Description |
|--------|-------------|
| **Total Spend** | Sum of all spend amounts |
| **Total Savings** | Sum of all savings amounts |
| **KPI %** | (Savings ÷ Spend) × 100 |
| **Spend by Category/Product** | Aggregated spend trends |

---

## 📈 Key Insights
- Visualized total spend trends over time to detect high-spending periods.  
- Identified top categories and products for potential cost savings.  
- Compared target vs actual spend to monitor budget adherence.

---

## 🖼️ Dashboard Screenshots
![Dashboard Overview](screenshots)  

---

## 🗂️ How to Reproduce
1. Download the sample data from `data_sample/spend_data_sample.csv`.  
2. Open Power BI and load the data.  
3. Use the star schema diagram in `schema_diagram.jpg` to create relationships.  
4. Build the visualizations as shown in the screenshots folder.

---

## 📊 Star Schema

This dashboard uses a star schema for efficient reporting and comparison of actual vs target data.

**Fact Tables:**
- **Actual_Data** – contains actual spend/units, planned budget, and savings
- **Target_Data** – contains target amounts

**Dimension Tables:**
- **Dim_Date** – year, month, quarter, and day for time analysis
- **Dim_Geo** – Geo and country  for geographic analysis
- **Dim_Product** – product and category for product-level analysis

Both fact tables are linked to all dimension tables with one-to-many relationships, enabling filtering and slicing in dashboard visuals.

![Star Schema](schema_diagram.png)
---

## ⚡ Notes
- All data used is anonymized for privacy.  
- Dashboard is intended for demonstration purposes and showcases end-to-end data modeling, DAX, and reporting skills.  

---

*Project by Thiago Nardi – Data Analyst | Power BI & SQL | DAX & Data Modeling Enthusiast*
