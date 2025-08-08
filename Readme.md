# ​ Superstore Sales Analysis

**A data analysis project using Python to uncover sales and profit insights from a Superstore dataset.**

---

##  Project Overview
This project performs a comprehensive analysis of retail sales data from a fictional Superstore. It explores sales and profitability trends by category, region, and time period, and uncovers key business insights through data cleaning, exploration, and visualization.

---

##  Dataset Details
- **Original File:** `Superstore.csv`
- **Cleaned Data:** `Superstore_Cleaned.csv` (processed with missing values, date formats, and duplicates handled)
- **Rows:** ~9,000  
- **Columns Include:** Order ID, Customer Name, Order Date, Ship Date, Category, Sub‑Category, Sales, Profit, Region, etc.

---

##  Tools & Technologies
- **Python**: Data manipulation with `pandas`, visualizations with `matplotlib` and `seaborn`
- **Jupyter Notebook**: Organized workflow and analysis (`.ipynb`)
- **VS Code**: Development environment

---

##  File Structure
SalesProject/
│
├── Superstore.csv
├── Superstore_Cleaned.csv
├── superstore_analysis.ipynb
└── README.md 

---

##  Key Steps Performed
1. **Data Cleaning**
   - Handled missing values smartly
   - Converted dates to `datetime`
   - Removed duplicates and reset index

2. **Exploratory Data Analysis (EDA)**
   - Sales by Category / Sub-Category
   - Profit analysis by Region
   - Monthly Sales Trend
   - Top 10 Products by Sales
   - Profit vs Sales relationships

3. **Business Insights**
   - Identified high-performing categories and states
   - Pinpointed opportunities and potential risk areas
   - Visualized trends and performance through charts

---

##  Insights & Takeaways
- *Technology* and *Office Supplies* dominate sales and profits.
- The *Western region* consistently outperforms others in both metrics.
- Some high-sales products yield low profits—highlighting pricing or discount issues.
- Seasonal sales peaks indicate opportunities for targeted marketing campaigns.

---

##  How to View This Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Superstore-Sales-Analysis.git
