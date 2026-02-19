# E-Commerce Sales Analytics & Dashboard

An end-to-end data analysis project exploring e-commerce transaction data. This project utilizes **Python** for deep-dive exploratory data analysis (EDA) and **Power BI** for interactive business intelligence reporting.

![Dashboard Preview](main_dashboard.png)

## 📌 Project Overview
The goal of this project is to analyze sales performance, customer behavior, and geographical trends to provide actionable business insights. The analysis covers order fulfillment, revenue metrics (Gross vs. Net), and regional sales distribution.

## 📂 File Structure
| File Name | Description |
| :--- | :--- |
| `E_Commerce_Analysis.ipynb` | Jupyter Notebook containing Python code for data cleaning, EDA, and preprocessing. |
| `E-Commerce-Analysis.pbix` | Power BI dashboard file (.pbix) with interactive visuals and DAX measures. |
| `sales_dataset.zip` | Raw input dataset containing ~129,000 order records. |
| `main_dashboard.png` | Static screenshot of the final Power BI dashboard. |

## 🚀 Key Features & Insights
- **Data Cleaning & EDA**: Python-based preprocessing to handle missing values and filter successful transactions.
- **AOV Analysis**: Calculation of **Average Order Value (AOV)**, distinguishing between Gross AOV (including cancellations) and Net AOV (actual realized value).
- **Geographic Trends**: Identification of high-performing regions (e.g., Hyderabad identified as the second-highest city by sales).
- **Interactive Dashboard**: A Power BI report to visualize sales trends, category performance, and shipping status at a glance.

## 🛠️ Tech Stack
- **Languages**: Python (Pandas, NumPy)
- **Visualization**: Matplotlib, Seaborn, Power BI
- **Environment**: Jupyter Notebook

## 📊 Methodology

### Step 1: Data Cleaning & Preprocessing (Python)
The raw dataset contained mixed date formats, null values, and inconsistent text casing. The `E_Commerce_Analysis.ipynb` notebook handles:
* **Data Cleaning:** Handling missing values in the `Amount` column by imputing the median.
* **Standardization:** Parsing dates into a unified `YYYY-MM-DD` format and normalizing City/State names.

### Step 2: Data Modeling & Visualization (Power BI)
The processed CSV files were imported into Power BI to create a **Star Schema** data model.
* **DAX Measures:** Calculated Key Performance Indicators (KPIs) such as *Total Revenue*, *Average Order Value (AOV)*, and *Cancellation Rate*.
* **Dashboarding:** Built a multi-section dashboard focusing on:
    1.  **Financial Performance:** Revenue trends and AOV analysis.
    2.  **Logistics:** Comparing "Amazon vs. Merchant" fulfillment performance.
    3.  **Customer Insights:** Geographic heatmaps of sales across India.
    4.  **Product Analysis:** Best-selling categories and SKU-level performance.

## 🚀 How to Run
1.  **Python Analysis:**
    * Open `E_Commerce_Analysis.ipynb` in Jupyter Notebook or VS Code.
    * Ensure `sales_dataset.csv` is in the same directory.
    * Run all cells to generate the cleaned CSV files.
2.  **Power BI Dashboard:**
    * Open `E-Commerce-Analysis.pbix` in Power BI Desktop.
    * *Note:* You may need to update the data source settings to point to the location of the CSV files on your local machine.

## 📬 Contact
If you have any questions or feedback, feel free to reach out!
* [LinkedIn](https://www.linkedin.com/in/ruchir-a-308240128/)
* [Email](ruchira559@gmail.com)
