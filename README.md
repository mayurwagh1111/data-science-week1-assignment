# E-Commerce Sales Analysis — Data Science Internship Week 1

## 📌 Project Overview
This project focuses on cleaning and analyzing an e-commerce dataset using Python and Pandas. The objective is to identify sales trends, calculate key performance indicators (KPIs), understand customer behavior, and create visualizations to support business decisions.

## 🎯 Objectives
- Inspect and clean raw e-commerce data.
- Handle missing values, duplicate records, and invalid data.
- Calculate important sales KPIs.
- Analyze monthly sales, product categories, customers, and cities.
- Create bar charts, line charts, and pie charts.
- Build a sales dashboard and prepare a final report.

## 📂 Dataset Description
The dataset contains 1,010 original rows and 11 columns.

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Customer ID | Customer identifier |
| Product Name | Name of the purchased product |
| Category | Product category |
| Quantity | Number of units purchased |
| Unit Price | Price per unit |
| Total Amount | Total transaction amount |
| Order Date | Date of the order |
| Payment Mode | Payment method |
| Delivery Status | Order delivery status |
| City | Customer/order city |

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git and GitHub

## 🧹 Data Cleaning
The following steps were performed:
- Inspected the dataset structure and data types.
- Identified missing values and duplicate records.
- Standardized column names and text categories.
- Replaced missing categorical and customer values with `Unknown`.
- Removed confirmed duplicate rows.
- Excluded records with invalid dates, non-positive quantities, or non-positive unit prices.
- Recalculated total amount using Quantity × Unit Price.
- Saved the cleaned dataset separately from the raw data.

## 📊 Sales KPIs
The project calculates:
- Total Revenue
- Total Orders
- Average Order Value
- Total Units Sold
- Top-Selling Category
- Top Revenue-Generating Product

## 👥 Customer and City Analysis
The analysis identified these results:
- **Top revenue-generating city:** Aurangabad
- **Revenue from Aurangabad:** ₹3,414,481
- **Repeat customers:** 264
- **Repeat-customer revenue share:** 97.91%

These findings apply to the current dataset and cleaning rules.

## 📈 Visualizations
The project includes:
1. Bar chart — Revenue by Product Category
2. Line chart — Monthly Sales Revenue Trend
3. Pie chart — Revenue Contribution by Category
4. Dashboard — KPI cards, category revenue, monthly revenue, and top cities

## 💡 Key Insights
- Aurangabad is the highest revenue-generating city in the current analysis.
- Repeat customers contribute a large share of recorded revenue.
- Category-level analysis helps compare product performance.
- Monthly sales analysis helps identify periods of higher and lower revenue.

## 📁 Recommended Repository Structure
```text
data-science-week1-assignment/
├── data/
│   ├── raw/
│   │   └── ecommerce_week1_raw.csv
│   └── cleaned/
│       └── ecommerce_cleaned.csv
├── notebooks/
│   └── week1_analysis.ipynb
├── outputs/
│   ├── charts/
│   └── dashboard/
├── reports/
│   └── final_report.md
├── README.md
└── requirements.txt
```

## ▶️ How to Run the Project
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `week1_analysis.ipynb` in Jupyter Notebook.
4. Place the raw CSV in the correct `data/raw/` folder.
5. Run the notebook cells from top to bottom.
6. Review the cleaned dataset, KPI summaries, charts, and report.

Install dependencies with:

```bash
pip install pandas matplotlib seaborn jupyter
```

## ⚠️ Limitations
- Results depend on the supplied dataset and data-cleaning decisions.
- Missing customer IDs may affect customer counts and repeat-customer calculations.
- Repeated order IDs require business-rule validation.
- Observed sales patterns do not prove the causes of revenue changes.

## ✅ Conclusion
This project demonstrates a basic end-to-end data analytics workflow, including data cleaning, KPI calculation, exploratory analysis, customer insights, visualization, and business reporting.

## 👤 Author
**Mayur Wagh**  
Data Science | Data Analytics | Python | SQL | Power BI
