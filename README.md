# Supply Chain & Operations Analysis

An end-to-end data analytics project focused on understanding supply chain performance, identifying inventory inefficiencies, analysing demand patterns, and evaluating opportunities to reduce operational costs.

## Problem Statement

Supply chain operations involve balancing product demand, inventory availability, supplier performance, and storage costs. Poor demand forecasting or inefficient inventory management can lead to stockouts, excess inventory, delayed deliveries, and increased operational expenses.

This project aims to analyse supply chain data and generate actionable insights to improve inventory planning, supplier performance, and overall operational efficiency.

## Project Objectives

- Analyse historical demand and identify sales trends and seasonal patterns.
- Evaluate supplier lead times and delivery performance.
- Measure inventory turnover and identify slow-moving products.
- Identify stockout risks and excess inventory.
- Develop demand forecasting models.
- Simulate inventory policies to evaluate reorder points and safety stock.
- Estimate potential cost savings and working capital improvements.

## Technology Stack

| Tool | Purpose |
|---|---|
| Python | Data analysis and forecasting |
| Pandas, NumPy | Data cleaning and manipulation |
| Matplotlib, Seaborn | Exploratory data analysis and visualization |
| SQL | Data extraction and business queries |
| Excel | Reporting and analysis |
| Power BI | Interactive dashboards |
| Scikit-learn / Statsmodels | Forecasting and model evaluation |

## Analysis Workflow

### 1. Data Understanding and Cleaning
- Inspect datasets and understand data distributions.
- Handle missing values and duplicate records.
- Identify inconsistent formats and invalid entries.
- Prepare datasets for analysis.

### 2. Exploratory Data Analysis
- Analyse product-wise and category-wise demand.
- Identify monthly and seasonal demand trends.
- Evaluate supplier delivery performance.
- Examine inventory levels and stockout patterns.

### 3. SQL Analysis
Use SQL to answer business questions such as:

- Which products have the highest demand?
- Which suppliers have the longest lead times?
- Which products experience frequent stockouts?
- What is the inventory turnover ratio?
- Which products contribute most to inventory holding costs?

### 4. Demand Forecasting
- Analyse historical demand patterns.
- Build baseline forecasting models.
- Compare forecasting performance using appropriate evaluation metrics.
- Identify products with changing demand patterns.

### 5. Inventory Optimization
- Calculate reorder points and safety stock.
- Evaluate inventory holding costs.
- Simulate different inventory replenishment policies.
- Compare stockout risks and inventory costs under different scenarios.

### 6. Dashboard and Business Insights
Develop an interactive Power BI dashboard to monitor:

- Total inventory value
- Inventory turnover
- Stockout rate
- Supplier lead time
- Demand trends
- Product-wise inventory performance
- Estimated inventory costs

## Key Business Metrics

| Metric | Purpose |
|---|---|
| Inventory Turnover | Measures how frequently inventory is sold and replenished |
| Stockout Rate | Measures the frequency of unavailable products |
| Supplier Lead Time | Measures the time taken by suppliers to deliver orders |
| Forecast Accuracy | Evaluates demand forecasting performance |
| Safety Stock | Determines additional inventory needed to manage uncertainty |
| Reorder Point | Identifies when new inventory should be ordered |
| Holding Cost | Estimates the cost of storing inventory |

## Expected Deliverables

- Cleaned and analysis-ready datasets.
- SQL queries for supply chain business questions.
- Python notebooks for EDA and demand forecasting.
- Inventory optimization and scenario simulation.
- Power BI dashboard.
- Business recommendations supported by analytical findings.

## Project Structure

```text
Supply-Chain-Operations-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_demand_forecasting.ipynb
│   └── 04_inventory_optimization.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboards/
│   └── supply_chain_dashboard.pbix
│
├── reports/
│   └── business_insights.md
│
├── requirements.txt
└── README.md
```

## Installation and Setup

1. Clone the repository:

```bash
git clone <YOUR_REPOSITORY_URL>
cd Supply-Chain-Operations-Analysis
```

2. Create a virtual environment:

```bash
python -m venv venv
```

3. Activate the environment:

Windows:
```bash
venv\Scripts\activate
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Open the Jupyter notebooks:

```bash
jupyter notebook
```

## Results and Business Recommendations

This section will contain validated findings after the analysis is completed, including:

- Demand forecasting performance.
- Products with high stockout risk.
- Suppliers with delivery delays.
- Inventory optimization opportunities.
- Estimated cost savings and working capital impact.

## Conclusion

This project demonstrates the application of Python, SQL, Excel, forecasting techniques, and Power BI to solve practical supply chain and inventory management problems. The goal is to transform operational data into measurable business insights that support better planning and decision-making.

---

**Project Domain:** Supply Chain Analytics | Operations Analytics | Business Intelligence

**Status:** In Progress
