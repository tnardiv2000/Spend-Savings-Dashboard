# Spend & Savings Dashboard

**Visualizing spend and savings patterns to optimize budgets and identify cost-saving opportunities.**

---

## 📌 Business Context
This project analyzes organizational spend data to highlight trends, identify savings opportunities, and support data-driven decision-making. The dashboard helps answer questions like:

- How has spending evolved over time?  
- Which departments or categories offer potential savings?  
- Are we staying within planned budgets?

---

## 📊 Data Overview
- **Data Source:** Anonymized spend and transaction data.  
- **Fields Included:** Date, Category, Department, Amount, Planned Budget, Savings.  
- **Data Model:** Star schema with one fact table (`Fact_Spend`) and four dimension tables (`Dim_Date`, `Dim_Category`, `Dim_Department`, `Dim_Budget`).  

**Sample Data:** (PowerBI_Target_Dataset.csv)(PowerBI_Actual_Full_Dataset.csv)

---

## 🛠️ Technical Stack
- **Power BI:** Dashboard creation and visualization  
- **DAX:** Key measures and calculations  
- **SQL:** Data extraction and transformation  
- **Data Modeling:** Star schema design for efficient reporting

---

## 🔑 Key Measures & Metrics
Some of the key metrics included in the dashboard:

| Metric | Description |
|--------|-------------|
| **Total Spend** | Sum of all spend amounts |
| **Total Savings** | Difference between Planned Budget and Actual Spend |
| **Savings %** | (Savings ÷ Planned Budget) × 100 |
| **Spend by Category/Department** | Aggregated spend trends |

*Full DAX measures available in `dax_measures.txt`*

---

## 📈 Key Insights
- Visualized total spend trends over time to detect high-spending periods.  
- Identified top departments and categories for potential cost savings.  
- Compared planned vs actual spend to monitor budget adherence.

---

## 🖼️ Dashboard Screenshots
![Dashboard Overview](screenshots/dashboard_overview.png)  
*(Additional screenshots can be added here)*

---

## 🗂️ How to Reproduce
1. Download the sample data from `data_sample/spend_data_sample.csv`.  
2. Open Power BI and load the data.  
3. Use the star schema diagram in `schema_diagram.png` to create relationships.  
4. Add the DAX measures from `dax_measures.txt`.  
5. Build the visualizations as shown in the screenshots folder.

---

## 📊 Star Schema Diagram
![Star Schema](schema_diagram.png)

---

## ⚡ Notes
- All data used is anonymized for privacy.  
- Dashboard is intended for demonstration purposes and showcases end-to-end data modeling, DAX, and reporting skills.  

---

*Project by Thiago Nardi – Data Analyst | Power BI & SQL | DAX & Data Modeling Enthusiast*
