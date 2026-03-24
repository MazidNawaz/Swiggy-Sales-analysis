# 🍽️ Swiggy Sales Analysis Dashboard

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

> An end-to-end sales analysis of Swiggy order data across India — covering city-wise performance, food categories, state-level revenue, quarterly trends, and weekly fluctuation patterns.

---

## 📊 Visualizations

### 🏙️ Top 5 Cities by Sales
![Top 5 Cities by Sales](Cities%20sales.png)

> Bengaluru leads by a significant margin (~5.3M INR), followed closely by Lucknow, Hyderabad, Mumbai, and New Delhi — all hovering around 3M INR.

---

### 🥗 Revenue Distribution by Food Category
![Revenue Distribution by Food Category](Food%20category.png)

> Vegetarian items dominate with **64.8%** of total revenue, while Non-Veg accounts for **35.2%** — indicating a strong veg-preference market across Swiggy's customer base.

---

### 📅 Quarterly Performance Summary
![Quarterly Performance Summary](Quarterly%20Sales.png)

> Q1 and Q2 2025 show strong sales (~20M INR each), while Q3 sees a notable dip to ~13M. Total orders and average ratings also trend downward across quarters, suggesting potential seasonal or market effects.

---

### 🗺️ Revenue by State (INR)
![Revenue by State](State%20wise%20sales.png)

> **Karnataka** tops all states with ~5.4M INR, followed by Uttar Pradesh, Telangana, and Maharashtra (~3M each). Northeastern states like Nagaland and Sikkim record the lowest revenues.

---

### 📈 Weekly Sales with Trend Line
![Weekly Sales with Trend Line](Weekly%20Sales.png)

> Weekly sales peak around **Feb 17–23, 2025** (marked as Peak Sales 🚀 at ~1.72M INR), then stabilize in the 1.4M–1.6M range. The 3-week moving average confirms a steady plateau after the early spike.

---

### 📉 Weekly Sales Trend (Fluctuation Analysis)
![Weekly Sales Trend - Fluctuation Analysis](Weekly%20Sales%20(Trend).png)

> A dedicated fluctuation view highlighting the sharp dip in the first week (Dec 30, 2024), rapid recovery through January, a peak in February, and a generally stable band through August 2025.

---

## 🔑 Key Insights

| # | Insight |
|---|---------|
| 1 | 🏙️ **Bengaluru** is Swiggy's top city by far, generating nearly **2x** the revenue of the next city |
| 2 | 🥦 **Veg food** dominates at **64.8%** of revenue — a key consideration for menu strategy |
| 3 | 📉 **Q3 2025** saw a significant revenue drop (~35% vs Q1/Q2), warranting further investigation |
| 4 | 🗺️ **Karnataka & UP** are the top two states — southern and northern India are key markets |
| 5 | 📆 **Feb 17–23** recorded peak weekly sales, possibly tied to a campaign or seasonal event |
| 6 | 📊 Sales stabilized at ~**1.5M/week** for most of 2025, showing consistent demand post-peak |

---

## 📁 Project Structure

```
📦 swiggy-sales-analysis
 ┣ 📊 Cities_sales.png
 ┣ 🥗 Food_category.png
 ┣ 📅 Quarterly_Sales.png
 ┣ 🗺️ State_wise_sales.png
 ┣ 📈 Weekly_Sales.png
 ┣ 📉 Weekly_Sales_(Trend_).png
 ┣ 📓 swiggy_analysis.ipynb       # Main analysis notebook
 ┣ 📋 swiggy_data.csv             # Raw dataset
 ┗ 📘 README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core language |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib** | Static charts |
| **Plotly / Seaborn** | Interactive & styled visualizations |
| **Jupyter Notebook** | Analysis environment |

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/swiggy-sales-analysis.git
   cd swiggy-sales-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas matplotlib plotly seaborn jupyter
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook swiggy_analysis.ipynb
   ```

---

## 🙋‍♂️ Author

**Your Name**
- GitHub: ([My-Github](https://github.com/MazidNawaz))
- LinkedIn: [My-linkedin](https://linkedin.com/in/mazid-nawaz-ahmad-49b0862b2)

---

> ⭐ If you found this useful, please give it a star — it helps others discover the project!
