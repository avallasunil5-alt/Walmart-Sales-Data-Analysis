# Walmart-Sales-Data-Analysis
# 🛒 Walmart Sales Analysis & Forecasting

A full-scale business intelligence and data science project analyzing Walmart’s weekly sales performance across **45 stores** using **Python analytics** and **Power BI dashboards**.

This project transforms raw retail data into **actionable insights** by examining how **economic, environmental, and seasonal factors** influence revenue patterns.

---

## 📌 Project Objectives

This project aims to:

- Analyze **store-level sales performance**
- Quantify the impact of **holidays, CPI, unemployment, fuel prices, and temperature**
- Detect **seasonal trends and anomalies**
- Enable **interactive decision-making** through Power BI dashboards
- Provide a **scalable data analytics workflow**

---

## 📂 Dataset Overview

The dataset contains **6,435 records** representing weekly sales data from **45 Walmart stores**.

| Feature | Description |
|-------|-------------|
| `Store` | Store number |
| `Date` | Week of sales |
| `Weekly_Sales` | Revenue for the given store |
| `Holiday_Flag` | 1 = Holiday week, 0 = Non-holiday |
| `Temperature` | Temperature on sales date |
| `Fuel_Price` | Fuel cost in the region |
| `CPI` | Consumer Price Index |
| `Unemployment` | Regional unemployment rate |

---

## 🧰 Technology Stack

### Data Science
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

### Business Intelligence
- Power BI (`.pbix`)

### Environment
- Jupyter Notebook  

---

## 🔍 Key Business Insights

### 📊 Sales Performance
- **Total Revenue:** ~$6.73 Billion  
- **Average Weekly Sales per Store:** ~$1.04 Million  

### 🏬 Store-Level Variation
- **Top Performer:** Store 4 (~$300M in sales)  
- **Lowest Performer:** Store 5 (~$45M)  
- Sales distribution shows **large operational inequality** across locations.

### 🎄 Holiday Effect
- Sales spike significantly during **holiday weeks**
- Confirms **seasonality as a major revenue driver**

### 📉 Economic Influence
- CPI and unemployment show measurable correlations with consumer spending
- Fuel prices and temperature impact customer mobility and purchasing behavior

---

## 📊 Power BI Dashboard

The interactive Power BI report allows:

- Store-wise filtering
- Year-wise sales analysis
- Holiday vs non-holiday comparison
- Trend and pattern detection
- High-level executive overview

Open:
```text
walmart.pbix
