# 📊 Food Price Visualization Project (WFP Dataset)

## 📝 Project Overview
This project explores global food price trends using the **World Food Programme (WFP) Food Prices Database**.  
Through Excel PivotTables and PivotCharts, the project visualizes commodity prices, compares retail vs wholesale markets, and highlights the cost distribution of common foods like bread, bananas, and apples.

The main goal is to **transform raw price data into clear insights** about food markets, price disparities, and cost structures across different commodities and regions.

---

## 🎯 Objectives
- Analyze and summarize food price data using **Excel PivotTables**.
- Visualize **average prices by commodity** using bar charts.
- Compare **retail vs wholesale price differences**.
- Show **relative prices of selected foods (bread, bananas, apples)** using a pie chart.
- Combine all visualizations into a **single interactive dashboard**.

---

## 🧩 Dataset
**Source:** World Food Programme (WFP)  
**File:** `wfp_food_prices_database.csv`

### Key Columns
| Column | Description |
|---------|-------------|
| `adm0_name` | Country name |
| `adm1_name` | Region or administrative area |
| `cm_name` | Commodity name (e.g., Bread, Bananas, Apples) |
| `mp_price` | Market price of the commodity |
| `mp_commoditysource` | Market type (Retail or Wholesale) |
| `mp_year` | Year of observation |
| `mp_month` | Month of observation |

---

## 📈 Visualizations

### 1. Bar Chart — Average Price by Commodity
Shows how different food commodities compare in terms of average price.  
**Pivot Setup:**
- Rows → `cm_name`
- Values → `mp_price` (Average)
- Chart Type → *Bar Chart*

### 2. Column Chart — Retail vs Wholesale Comparison
Highlights price differences between retail and wholesale markets.  
**Pivot Setup:**
- Rows → `cm_name`
- Columns → `mp_commoditysource`
- Values → `mp_price` (Average)
- Chart Type → *Clustered Column Chart*

### 3. Pie Chart — Bread vs Bananas vs Apples
Shows the proportional average prices of three popular commodities.  
**Pivot Setup:**
- Rows → Filtered `cm_name` (Bread, Bananas, Apples)
- Values → `mp_price` (Average)
- Chart Type → *2D Pie Chart*

### 4. Dashboard
All charts are combined in a single sheet with slicers for:
- Country
- Year
- Market Type (Retail / Wholesale)

---

## ⚡ Key Insights (Aha Moments)
- PivotTables simplified large-scale price analysis instantly.  
- Retail prices are consistently higher than wholesale prices — indicating market markups.  
- Bar charts revealed which commodities drive overall price levels.  
- The pie chart showed clear proportional differences among bread, bananas, and apples.  
- The integrated dashboard told a complete visual story, transforming raw data into actionable insights.

---

## 🛠 Tools Used
- **Microsoft Excel**
  - PivotTables and PivotCharts
  

---

## 🚀 How to Use This Project
1. Download `wfp_food_prices_database.csv`.
2. Open in Excel.
3. Insert PivotTables and build:
   - Bar chart (Average prices)
   - Retail vs Wholesale chart
   - Bread–Bananas–Apples pie chart
4. Combine all visuals in one sheet named **Dashboard**.
5. Add slicers for region, country, or year for interactivity.

---

## 📚 Learning Outcomes
- Mastery of Excel PivotTables and PivotCharts.
- Understanding of food price structures across markets.
- Ability to transform data into dashboards that communicate insights clearly.
- Experience in storytelling with data visualization.

---

## 👨‍💻 Author
**Immanuel King’e Goko**  
Economics & Data Analysis Student  
Project: *Food Price Visualization using WFP Data*

---

## 🏁 License
This project is for **academic and educational purposes only**.  
Data © World Food Programme (WFP).
```

---

Would you like me to generate this as a **downloadable `README.md` file** (for GitHub or submission)? I can create it instantly for you.

