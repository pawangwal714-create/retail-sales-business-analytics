# Retail Sales & Business Performance Analytics

**End-to-End Data Analysis using Python, SQL, Excel and Power BI**

## Project Overview
This portfolio project simulates a retail analytics workflow from messy transaction data through cleaning, SQL analysis, Excel reporting, Power BI dashboard design, and business recommendations.

## Business Problem
Management needs a reliable view of revenue, profit, customers, products and regions, while also identifying data-quality problems before metrics reach decision-makers.

## Key Results
- **Total Sales:** ₹69,159,676
- **Total Profit:** ₹23,732,431
- **Orders:** 18,509
- **Customers:** 2,199
- **Average Order Value:** ₹3,737
- **Profit Margin:** 34.3%

## Tools
- Python / Pandas
- SQL
- Excel
- Power BI
- GitHub-ready documentation

## Workflow
`Raw CSV → Python Cleaning → Data Quality Validation → SQL Analysis → Excel Reporting → Power BI Dashboard → Insights → Recommendations`

## Data
The project contains a raw transaction file with intentionally realistic quality issues and a cleaned analysis-ready file. Master customer/product tables are also included for reproducibility.

## Data Cleaning
The workflow checks duplicates, missing values, inconsistent text, invalid quantities, excessive discounts and negative sales. Trusted product/customer master attributes are used to recover descriptive fields where possible.

## SQL
The SQL folder contains database setup, data-quality checks, 20 business analysis questions and advanced window-function examples.

## Excel
The workbook contains executive KPIs, data-quality checks, category/product/region/customer analysis, monthly trends and formula examples.

## Power BI
A real `.pbix` binary cannot be generated in this environment without Power BI Desktop. Instead, the project includes a Power BI setup guide with the recommended star schema, DAX measures and page designs, plus a dashboard mockup generated from the actual dataset.

## Key Insights
See `reports/business_insights.md`.

## Recommendations
See `reports/business_recommendations.md`.

## Reproduction
1. Open `python/data_cleaning_analysis.ipynb`.
2. Run the notebook from the project root.
3. Load `data/customer_master.csv`, `data/product_master.csv` and `data/cleaned_sales_data.csv` into your SQL engine.
4. Run the SQL scripts in order.
5. Open `excel/Retail_Sales_Analysis.xlsx`.
6. Follow `powerbi/powerbi_setup_guide.md` to recreate the Power BI report.

## Limitations
This is a portfolio simulation using synthetic retail data. It does not represent Crossing Infotech's internal data or processes.
