# Honduras Market Data Analysis: Clean, EDA & KPIs

This repository contains an End-to-End Data Analytics project focused on processing, cleaning, and extracting business insights from a retail market dataset based in Honduras. The project covers the full pipeline from raw data handling to key performance indicator (KPI) tracking and visualization.

## 📌 Project Overview
The main goal of this project is to transform unpolished sales and shipping data into actionable business intelligence. Through data cleaning and Exploratory Data Analysis (EDA) using Python, this notebook handles structural data issues, manages outliers, and surfaces trends regarding revenue distribution and customer purchasing behavior.

## 🛠️ Key Features & Data Pipeline

### 1. Data Cleaning & Imputation
* **Handling Missing Values:** Dropped missing financial rows lacking critical data and handled shipping date gaps by applying median imputation to maintain dataset integrity.
* **Outlier Management:** Utilized the Interquartile Range (IQR) method to detect and analyze statistical outliers in revenue and shipping rates.

### 2. Feature Engineering & KPI Calculation
Computed vital business metrics to evaluate market performance:
* **Total Revenue:** Aggregated overall sales to measure market scale.
* **Average Ticket (AOV):** Calculated the mean order value to analyze customer spending power.
* **Category Contribution:** Measured the revenue share percentage across different product types.

### 3. Exploratory Data Analysis (EDA) & Visualization
* Implemented **Seaborn** and **Matplotlib** to design clear, informative visual structures.
* Built distribution charts and categorical bar plots to visually identify the top-performing sectors and revenue drivers.

## 💻 Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
