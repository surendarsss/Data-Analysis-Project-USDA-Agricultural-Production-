# Data Analysis Project – USDA Agricultural Production 📊🚜

## Overview
This project demonstrates **data analysis using SQL** on agricultural production datasets, simulating work as a **Data Scientist at the USDA**. The goal is to generate **state-wise insights, trends, and anomalies** across commodities including **milk, cheese, coffee, honey, and yogurt**.

The project reflects **real-world business analysis**, providing data-driven recommendations for planning, reporting, and strategic decision-making.

---

## Business Analysis Context 💼
As a Data Scientist, the focus is not only on running queries but also on **extracting actionable insights** to guide decisions:

- **Commodity Performance:** Identify top-producing states and production trends over years.  
- **Targeted Planning:** Focus marketing, distribution, or resource allocation on high-performing states.  
- **Anomaly Detection:** Spot unusually high or low production for investigation.  
- **Cross-Commodity Insights:** Understand relationships between commodities to support planning.  
- **Data Completeness:** Detect missing or inconsistent production data.

> This approach mirrors **real USDA decision-support workflows**, showing both technical and business impact.

---

## Datasets 📁
| Dataset | Description |
|---------|-------------|
| milk_production | Yearly milk production by state |
| cheese_production | Monthly cheese production by state |
| coffee_production | Yearly coffee production by state |
| honey_production | Yearly honey production by state |
| yogurt_production | Yearly yogurt production by state |
| state_lookup | List of U.S. states with ANSI codes |

> Numeric values are stored **without commas** for SQL aggregation and analysis.

---

## Tools & Technologies 🛠️
- SQL (PostgreSQL / MySQL)  
- Optional: Excel/Tableau for visualization  


---

## Our Analysis 📸

### 1: Total Milk Production (2023)
![Milk Production](visuals/milk_2023.png)

### 2: States with Cheese Production > 100M in April 2023
![Cheese Production](visuals/cheese_april2023.png)

### 3: Coffee Production Trends
![Coffee Trends](visuals/coffee_trends.png)

### 4: Average Honey Production (2022)
![Honey Production](visuals/honey_2022.png)

### 5: State ANSI Codes (e.g., Florida)
![State ANSI Codes](visuals/state_ansi.png)

### 6: Cheese Production Including Zero-Production States (April 2023)
![Cheese Zero Production](visuals/cheese_zero_april2023.png)

### 7: Total Yogurt Production (2022) for States with Cheese Data (2023)
![Yogurt Production](visuals/yogurt_2022.png)

### 8: States Missing Milk Production in 2023
![Missing Milk States](visuals/missing_milk_2023.png)

### 9: Delaware Cheese Production (April 2023)
![Delaware Cheese](visuals/delaware_cheese.png)

### 10: Average Coffee Production for Years Where Honey Production > 1M
![Coffee Avg Honey](visuals/coffee_avg_honey.png)


---

## Practice Questions & Analysis 📝
1. **Total Milk Production (2023)** – Yearly reporting  
2. **States with Cheese Production > 100M in April 2023** – Marketing focus  
3. **Total Coffee Production (2011)** – Trend analysis  
4. **Average Honey Production (2022)** – Honey Council meeting preparation  
5. **State ANSI Codes** – Verify Florida code  
6. **Cheese Production Including Zero-Production States (April 2023)**  
7. **Total Yogurt Production (2022) for States with Cheese Data (2023)** – Dairy Division planning  
8. **States Missing Milk Production in 2023** – Identify gaps  
9. **Check Delaware Cheese Production (April 2023)** – Verify presence/absence  
10. **Average Coffee Production for Years Where Honey Production > 1M** – Cross-commodity insights

---

## Key Insights 🔑
- **Top States Identified:** e.g., California, Texas, Florida  
- **Trends Observed:** Year-over-year production growth or decline  
- **Anomalies Detected:** Unusually high/low production in certain states or years  
- **Cross-Commodity Patterns:** Correlations like honey vs coffee production  
- **Missing Data:** States with missing milk or cheese production identified

---



---

## Author ✍️
**Surendar S**  
Phone:7010861982
Email: surendarpc936@gmail.com  

---
