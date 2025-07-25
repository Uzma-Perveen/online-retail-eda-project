# 🛍️ Online Retail Sales EDA + Dashboard
This project performs a complete **Exploratory Data Analysis (EDA)** and **interactive dashboarding** using a real-world online retail dataset. It includes data cleaning, visual insights, customer segmentation (RFM), and a Power BI dashboard — all aligned with project objectives.
---
## 📘 Project Objective
This project fulfills the following goals as outlined in the official assignment PDF:
- Clean and preprocess retail sales data from 2010–2011
- Perform EDA using **Python (Pandas, Seaborn, Matplotlib)**
- Identify patterns by **product, country, time, and customer behavior**
- Build customer **RFM segments** for loyalty analysis
- Create an interactive **Power BI Dashboard** with 4 focused pages
---
## 📂 Files Included
| File Name | Description |
|-----------|-------------|
| `Online_Retail_EDA.ipynb` | Jupyter Notebook with all data cleaning, EDA, and RFM analysis |
| `Online_Retail_EDA_Dashboard.pbix` | Power BI dashboard file |
| `Cleaned_Online_Retail.csv` | Full cleaned dataset (excluded from GitHub due to size) |
| `RFM_Segmentation.csv` | Table of customer RFM scores and segments |
| `README.md` | Full project overview and documentation |
---
## 🧪 Technologies Used
- **Python 3**
  - `pandas`, `matplotlib`, `seaborn`, `datetime`
- **Jupyter Notebook**
- **Power BI Desktop**
- **GitHub** for hosting project code and files
---
## 🔎 EDA Breakdown (in Python)
### 1️⃣ Data Cleaning:
- Removed duplicates and missing values (e.g., `Customer ID`, `Description`)
- Filtered out canceled orders (`Invoice` starting with "C")
- Removed outliers (negative or zero Quantity/Price)
- Converted `InvoiceDate` to datetime
- Created `TotalAmount = Quantity * Price`

### 2️⃣ General Analysis:
- Total: 4338 unique customers, 3665 products, 18532 transactions
- Sales from 37 countries

### 3️⃣ Product Insights:
- Top 10 products by quantity and revenue
- Identified zero-priced products (data errors)
- Plotted bar charts for bestsellers

### 4️⃣ Customer Analysis:
- Top 10 customers by volume and frequency
- Purchase distribution per customer (histogram)
- Identified loyal customers

### 5️⃣ Time Series Analysis:
- Monthly revenue trend (line chart)
- Day-of-week transaction patterns (bar chart)
- Peak months: Nov-Dec

### 6️⃣ Country Insights:
- Bar chart and map for sales by country
- UK dominant, followed by Netherlands, Germany, France

### 7️⃣ RFM Segmentation:
- Calculated Recency, Frequency, Monetary values
- Scored each customer (1–5 scale)
- Segmented into: Champions, Loyal, Potential, At Risk
- Scatter plot: Frequency vs Monetary by Segment
---
## 📊 Power BI Dashboard
The `.pbix` file contains 4 pages:
### 1️⃣ Sales Overview
- KPIs: Total Revenue, Orders, Customers
- Line chart: Monthly sales trend
### 2️⃣ Top Products
- Bar charts: Top 10 by Quantity and Revenue
- Treemap: Product category breakdown
### 3️⃣ Customer Segments
- Table: Full RFM table with scores and segment names
- Scatter plot: Frequency vs Monetary
- Bar chart: Top loyal customers
### 4️⃣ Geographical Insights
- Map visual: Revenue by country
- Bar chart: Top 10 countries by revenue
---
## 📌 Dataset Source
Kaggle – [Online Retail II Dataset](https://www.kaggle.com/datasets/vijayuv/onlineretail)
---
## 📩 Questions?
Feel free to fork, star ⭐, or connect with me on GitHub!
