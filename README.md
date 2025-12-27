# Customer _behavior _data_analysis

This project analyzes customer shopping behavior using transactional data to uncover patterns in purchases, revenue, and customer segments. It is part of an academic/portfolio project to practice real-world data analytics using SQL, Python, and Power BI. [web:40][web:150]

## Project Overview

The goal of this project is to understand how customers shop:  
- Which products and categories are most popular  
- How much revenue different customer groups generate  
- What overall purchase patterns look like over time  

The analysis is built end-to-end: from raw CSV data, to SQL queries, to an interactive Power BI dashboard. [web:40][web:150]

## Dataset

- **File:** `customer_shopping_behavior.csv`  
- **Description:** Contains individual customer shopping transactions, including basic details about customers, items purchased, and spending behavior. [web:150][web:153]  
- **Source:** Public sample dataset for customer shopping behavior (suitable for practice and learning). [web:150]

## Tech Stack

- **Database:** MySQL (data storage and SQL analysis) [web:40]  
- **Analysis:** Jupyter Notebook (`first project.ipynb`) with Python (Pandas, basic EDA) [web:144]  
- **Visualization:** Power BI (`project1.pbix`) for interactive dashboards [web:150]  

## Repository Contents

- `customer_shopping_behavior.csv` – Raw customer transaction dataset used for analysis. [web:150]  
- `first project.ipynb` – Jupyter Notebook with data cleaning, exploratory data analysis (EDA), and basic visualizations. [web:144]  
- `project1.sql` – MySQL script for table creation and SQL queries used to explore customer behavior. [web:153]  
- `project1.pbix` – Power BI report file containing dashboards built on top of the processed data. [web:150]

## Key Analysis & Insights

Examples of questions this project can answer: [web:40][web:153]  
- Which products or categories are most frequently purchased?  
- What is the revenue contribution of different customer segments or age groups?  
- How do customer purchases vary by time (day/month/season)?  

The Power BI dashboard helps stakeholders quickly see trends, top customers/products, and summary KPIs. [web:150][web:156]

## How to Run This Project

1. **MySQL Setup**  
   - Create a database in MySQL.  
   - Run `project1.sql` to create tables and (optionally) load data. [web:40][web:153]

2. **Jupyter Notebook**  
   - Open `first project.ipynb` in Jupyter Notebook or VS Code.  
   - Install required Python libraries (for example: `pandas`, `numpy`, `matplotlib`). [web:146][web:155]  
   - Run the cells to reproduce the EDA and basic analysis.

3. **Power BI Dashboard**  
   - Open `project1.pbix` in Power BI Desktop.  
   - Update the data source connection if needed (MySQL or CSV path).  
   - Refresh the data to see updated visuals. [web:52][web:150]

## Future Improvements

- Add more advanced segmentation (RFM, churn analysis). [web:36][web:153]  
- Include more DAX measures in Power BI for deeper business KPIs. [web:52]  
- Automate data refresh pipeline between MySQL and Power BI. [web:46]

## Author

- **Prashanth** – MCA student, interested in data analytics, SQL, and Power BI dashboards. [memory:6][web:145]

