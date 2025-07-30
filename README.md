# 🛍️ Customer Segmentation Using RFM Analysis

This project is part of **Elevvo Pathways Task 2**, aimed at performing in-depth analysis of online retail data. The goal is to understand customer purchasing behavior, calculate revenue, and explore key trends in sales data using Python’s powerful data analysis libraries.

## 📌 Objective

- Load and analyze a real-world retail dataset
- Perform calculations like **Total Revenue**, **most sold items**, and **high-value customers**
- Gain insights into **sales patterns** using data exploration techniques

---

## 📂 Files Included

- `Elevvo Pathways Task 2.ipynb` – Jupyter Notebook with full analysis code
- `online_retail.csv` – CSV file containing transaction data (uploaded via Colab)

---

## 📊 Dataset Overview

The dataset includes transaction-level data from an online retail store. Key columns:

| Column Name | Description |
|-------------|-------------|
| Invoice   | Unique ID for each transaction |
| StockCode   | Product/item code |
| Description | Item description |
| Quantity    | Number of items purchased |
| Price       | Price per item |
| InvoiceDate | Date and time of the transaction |
| Customer ID  | Unique ID for customer |
| Country     | Country of the customer |

---

## 🔎 Steps Performed

1. **Data Import**  
   - CSV file is uploaded using Google Colab's `files.upload()` method.
   - Data is read into a pandas DataFrame for analysis.

2. **Data Cleaning**  
   - Checked for missing values and removed incomplete rows.
   - Filtered out negative or zero quantities and prices.

3. **Feature Engineering**  
   - Created a new column `TotalPrice = Quantity × Price` to calculate revenue per item.

4. **Exploratory Data Analysis (EDA)**  
   - Calculated total revenue.
   - Identified top-selling products by quantity and revenue.
   - Analyzed customer spending behavior.
   - Grouped sales data by country for geographic insights.

5. **Visualizations**  
   - Bar charts for top products
   - Pie charts for sales by country
   - Line plots for time series sales trends

## 📈 Key Insights (Example)

- Top 5 products contributed to 40% of total revenue.
- UK had the highest number of purchases.
- A small group of customers generated the majority of revenue (Pareto principle).

## 🔧 Tools & Libraries

- **Python**
- **Pandas** – Data manipulation
- **Matplotlib – Data visualization
- **Google Colab / Jupyter Notebook** – Interactive coding environment
- Excel (for initial data cleaning)

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Upload the dataset when prompted (`online_retail.csv`).
3. Run all code cells step-by-step.
4. Review outputs and visualizations.



