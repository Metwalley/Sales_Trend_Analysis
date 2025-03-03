# Sales Trend Analysis - Superstore Dataset

## 📌 Project Overview

This project is a comprehensive **Sales Trend Analysis** using the **Superstore Dataset**. The goal was to identify **sales trends, seasonal patterns, and anomalies** while also analyzing profitability and regional performance.

We performed in-depth **data cleaning, exploratory data analysis (EDA), and visualizations** to uncover insights that businesses can use to optimize sales and pricing strategies.

---

## 📊 Dataset Details

- **Dataset:** [Superstore Sales Data](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Rows:** 9,994
- **Columns:** 13
- **Key Features:**
  - `Order Date`, `Ship Date`: Timestamps for orders
  - `Sales`, `Profit`: Revenue and profitability figures
  - `Quantity`, `Discount`: Order quantities and discount rates
  - `Category`, `Sub-Category`: Product classification
  - `Region`, `State`, `Segment`: Customer demographics

---

## 🎯 Objectives

- Analyze **sales trends over time** to detect patterns.
- Identify **seasonal variations** and **sales anomalies**.
- Compare **sales performance by region, state, and customer segment**.
- Evaluate **profitability vs. sales trends** to optimize business decisions.

---

## 📌 Analysis Steps & Key Findings

### **1️⃣ Data Cleaning & Preparation**

✅ Checked for **missing values** (none found). ✅ Checked for **duplicates** (none found). ✅ Converted **date columns** to datetime format. ✅ Stripped extra spaces from categorical data. ✅ Ensured data consistency before analysis.

---

### **2️⃣ Outlier Detection**

✅ Used **boxplots** to check for outliers in:

- `Sales`, `Quantity`, `Profit` ✅ Outliers found in **high-value tech products** and **bulk office supply orders**, but they were **valid business cases**. ✅ Decision: **Kept outliers** as they represent **real high-value sales.**

---

### **3️⃣ Sales Trend Analysis**

✅ Grouped **sales by year and month** to identify patterns. ✅ **Key Observations:**

- 📉 **January to February drop** across all years (except 2016).
- 📈 **Massive February to March spike** every year.
- 📉 **March to April sales drop**, likely due to post-Q1 slowdown.
- 📌 **March had the highest sales, February the lowest**. ✅ **Actionable Insights:**
- Run **promotions in February** to mitigate the dip.
- **Increase marketing spend in March** to capitalize on natural demand.

📊 **Visualizations Used:**

- Line Chart (**Sales Trends Over Time** - Plotly)
- Interactive Dropdown Filters (**Year Selector**)

---

### **4️⃣ Regional Sales & Customer Segment Analysis**

✅ **Analyzed Sales by Region, State, and Customer Segment.** ✅ **Key Findings:**

- 🏆 **Top-selling regions:** West & East.
- 🚨 **Low-profit sub-categories:** Tables (Furniture), Machines (Tech), Supplies (Office).
- 👥 **Corporate customers contributed most revenue**. ✅ **Actionable Insights:**
- Adjust **pricing on low-profit categories**.
- Optimize **discount strategies in high-sales, low-profit regions**.

📊 **Visualizations Used:**

- Choropleth Map (**Sales by State** - Plotly)
- Bar Chart (**Profitability by Region & Segment**)

---

### **5️⃣ Profitability Analysis**

✅ Compared **Sales vs. Profit** using a dual-axis chart. ✅ **Key Findings:**

- 📈 Some **high-sales months had low profitability** due to heavy discounting.
- 🔻 Some categories had **negative profit margins despite high sales**. ✅ **Actionable Insights:**
- Reduce **aggressive discounting on Machines & Furniture**.
- Focus on **high-margin products for long-term growth**.

📊 **Visualizations Used:**

- **Dual-Axis Line Chart** (Sales vs. Profit Trends)
- **Bar Chart** (Profitability by Category)

---

## 💻 Technologies Used

- **Python (Pandas, NumPy)** - Data Processing
- **Seaborn & Matplotlib** - Exploratory Data Analysis
- **Plotly** - Interactive Visualizations
- **Google Colab / VSCode** - Development Environment
- **GitHub** - Version Control & Documentation

---

## 🚀 How to Run This Project

1️⃣ Clone the repository:

```bash
git clone https://github.com/yourusername/sales-trend-analysis.git
```

2️⃣ Install dependencies:

```bash
pip install pandas numpy seaborn plotly us
```

3️⃣ Open the Jupyter Notebook or VSCode and run `Sales_Trend_Analysis.ipynb`

---

## 📌 Final Thoughts

This analysis provided deep insights into **seasonal trends, regional performance, and profitability issues**. Businesses can use these findings to **optimize pricing, adjust discount strategies, and plan marketing efforts for maximum profitability**.

📢 **Next Steps:**

- Automate this analysis for real-time monitoring.
- Build an **interactive Power BI dashboard** for executives.
- Expand analysis to **predictive modeling (Sales Forecasting).**

🔗 **Author:** [Abdul-Rahman Metwalley](https://github.com/Metwalley)

📩 Feel free to contribute, fork, or contact me for improvements! 🚀
