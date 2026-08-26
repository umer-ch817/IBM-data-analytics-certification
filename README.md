# IBM-data-analytics-certification

# IBM Data Analyst Professional Certificate — Project Work

This repository contains hands-on projects completed as part of the **IBM Data Analyst Professional Certificate** on Coursera. Each project applies core data analysis skills — data extraction, cleaning, pivoting, visualization, and dashboard building — using Python and Excel.

## 📁 Files in this Repository

### 1. `Revenue_Data_and_Building_a_Dashboard_v1.ipynb`
**Skill:** Python for Data Science (Web Scraping, APIs, Data Visualization)

A Jupyter Notebook project on **Extracting and Visualizing Stock Data**. It covers:
- Extracting historical stock data (Tesla `TSLA` and GameStop `GME`) using the `yfinance` API.
- Web scraping quarterly revenue data for both companies using `requests` and `BeautifulSoup`.
- Cleaning scraped data (removing `$`, `,`, null values) with `pandas`.
- Building a custom `make_graph()` function with `matplotlib` to plot stock closing price against revenue on a dual dashboard.
- Final output: side-by-side stock price vs. revenue dashboards for Tesla and GameStop (data up to June 2021).

**Tools:** `yfinance`, `pandas`, `BeautifulSoup`, `matplotlib`
[File Name](Revenue_Data_and_Building_a_Dashboard_v1.ipynb)
---

### 2. `Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.xlsx`
**Skill:** Excel for Data Analysis (Data Preparation)

Raw dataset of Montgomery County's fleet equipment inventory (54 rows), listing each **Department**, **Equipment Class**, and **Equipment Count**. This is the starting/cleaned dataset used as the foundation for pivot table analysis in Part 2.
[File Name](Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.xlsx)
---

### 3. `Montgomery_Fleet_Equipment_Inventory_FA_PART_2_START.xlsx`
**Skill:** Excel for Data Analysis (PivotTables & Summarization)

Builds on Part 1 by adding three PivotTables to summarize the fleet inventory data:
- **Pivot Table 1:** Total equipment count by Department.
- **Pivot Table 2:** Equipment count broken down by Department and Equipment Class.
- **Pivot Table 3:** Equipment count broken down by Equipment Class and Department (reversed grouping).

Demonstrates the ability to summarize and re-slice raw data using multiple pivot perspectives.
[File Name](Montgomery_Fleet_Equipment_Inventory_FA_PART_2_START.xlsx)
---

### 4. `CarSalesByModelEnd.xlsx`
**Skill:** Excel for Data Analysis (PivotTables & Charts — Dashboard Building)

A car sales dataset (3,000+ transaction rows in `Sheet1`) analyzed through four PivotTables and matching charts:
- **Quantity Sold by Dealer ID** — with chart.
- **Profit by Date and Model** — with chart.
- **Profit by Year and Dealer ID** — with chart.
- **Sum of Profits for the Hudson Model** — with chart.

Demonstrates building multiple analytical views and visualizations from a single raw sales dataset.
[File Name](CarSalesByModelEnd.xlsx)
---

## 🛠️ Skills Demonstrated
- Data extraction via API (`yfinance`) and web scraping (`BeautifulSoup`)
- Data cleaning and preprocessing with `pandas`
- Data visualization with `matplotlib`
- Excel PivotTables for multi-dimensional data summarization
- Excel chart creation for dashboard-style reporting

## 👤 Author
**Muhammad Umer Hameed**
Final-Year Computer Science Student, University of Central Punjab (UCP)
IBM Data Analyst Professional Certificate — Coursera
