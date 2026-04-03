#  Swiggy Sales Analysis — End-to-End EDA Project

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-10B981?style=for-the-badge"/>
</p>



## 📌 Project Overview

This project performs a full **Exploratory Data Analysis (EDA)** on Swiggy food order data across multiple Indian cities and states. The goal is to uncover revenue patterns, customer behaviour trends, and city/state-wise performance using Python-based data analysis and visualization.

> **Dataset:** Real-world style Swiggy order data covering states, cities, restaurants, dish names, prices, ratings, and order dates.



## 📋 Business Requirements (BRD)

### KPIs to Calculate

| KPI | Description |
|-----|-------------|
| **Total Sales (₹)** | Overall revenue generated from food orders |
| **Average Rating** | Customer satisfaction level across all restaurants |
| **Average Order Value (₹)** | Revenue per individual order |
| **Ratings Count** | Total number of customer reviews submitted |
| **Total Orders** | Complete count of food orders in the dataset |

### Charts to Build

| Chart | Type |
|-------|------|
| Monthly Sales Trend | Line Chart |
| Daily Sales Trend | Bar Chart |
| Total Sales by Food Type (Veg vs Non-Veg) | Donut Chart |
| Total Sales by State | Horizontal Bar Chart |
| Quarterly Performance Summary | Aggregated Table |
| Top 5 Cities by Sales | Horizontal Bar Chart |
| Weekly Trend Analysis | Bar Chart |



## 📈 Key Insights

- 🏆 **Q3 was the best quarter** — highest revenue, most orders, and top average rating
- 🏙️ **Bengaluru leads all cities**, contributing ~25% of total platform revenue
- 🥗 **Veg food dominates at 62%** of orders, but Non-Veg shows higher per-order value
- 📅 **Fri–Sun drives ~45% of weekly revenue** — ideal window for promotional campaigns
- 🗺️ **South India dominates** — 3 of the top 5 revenue cities are from southern states
- ⭐ **Ratings stay consistently above 4.1** across all quarters — strong service quality



## 🗂️ Repository Structure

```
swiggy-sales-analysis/
│
├── Swiggy_Sales_Analysis.ipynb        # Main Jupyter Notebook (full EDA)
├── swiggy_data.xlsx                   # Dataset (order-level data)
├── Swiggy_Sales_Analysis_Deck.pptx    # Presentation deck (10 slides)
└── README.md                          # Project documentation
```



## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.10+** | Core programming language |
| **Pandas** | Data loading, cleaning, grouping |
| **NumPy** | Numerical operations |
| **Matplotlib** | Static chart generation |
| **Seaborn** | Enhanced static visualizations |
| **Plotly Express** | Interactive charts (pie, bar, trend) |
| **Jupyter Notebook** | Development & presentation environment |
| **Excel (.xlsx)** | Raw dataset source |



## ⚙️ Setup & Usage

**1. Clone the repository**
```bash
git clone https://github.com/gautam9892/Swiggy-Sales-Analysis.git
cd Swiggy-Sales-Analysis
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl jupyter
```

**3. Run the notebook**
```bash
jupyter notebook Swiggy_Sales_Analysis.ipynb
```



## 📽️ Presentation

A 10-slide presentation (`Swiggy_Sales_Analysis_Deck.pptx`) is included covering:

| Slide | Content |
|-------|---------|
| 01 | Title Slide |
| 02 | Project Overview & Tools Used |
| 03 | Business Requirements (BRD) — KPIs & Charts Required |
| 04 | KPI Dashboard |
| 05 | Sales Trend Analysis (Monthly & Weekly) |
| 06 | Category & Day-wise Breakdown (Daily + Veg vs Non-Veg) |
| 07 | Geographic & Quarterly Performance |
| 08 | State-wise Revenue Distribution |
| 09 | Key Insights & Findings |
| 10 | Thank You |



## 👤 Author

**Gautam Kumawat**


[![LinkedIn](https://img.shields.io/badge/LinkedIn-gautam9892-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/gautam9892/)
[![GitHub](https://img.shields.io/badge/GitHub-gautam9892-181717?style=flat&logo=github)](https://github.com/gautam9892)
[![Portfolio](https://img.shields.io/badge/Portfolio-gautamkumawat.vercel.app-FC8019?style=flat&logo=vercel)](https://gautamkumawat.vercel.app/)



> *This project is part of my Data Analytics portfolio. Feel free to fork, explore, or reach out for collaboration!*
