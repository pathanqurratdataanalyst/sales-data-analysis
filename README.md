# Superstore Sales Data Analysis

## Project Overview
This project explores Superstore sales data using Python to identify business trends, evaluate profitability, and understand customer and regional performance.

The objective is to transform raw sales data into meaningful insights that can support better business decisions.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
sales-data-analysis/
│
├── Images/
│   └── sales_dashboard.png
│
├── .gitignore
├── README.md
├── Sales_Analysis.ipynb
│
├── category_analysis.csv
├── customer_analysis.csv
├── monthly_sales.csv
├── regional_analysis.csv
└── subcategory_analysis.csv
```

## Analysis Performed
1. Data inspection and cleaning
2. Key business performance metrics
3. Sales and profit analysis by category
4. Sub-category performance analysis
5. Regional sales and profit analysis
6. Monthly sales trend analysis
7. Customer performance analysis
8. Discount and profit correlation
9. Dashboard creation

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Sales | 2,177,727.36 |
| Total Profit | 274,266.26 |
| Total Orders | 4,746 |
| Total Customers | 804 |
| Average Order Value | 458.86 |

## Key Findings
- Technology generated the highest sales and profit among the three categories.
- Furniture generated substantial sales but comparatively low profit.
- Copiers were the most profitable sub-category.
- Tables, Bookcases and Supplies recorded negative profits.
- The West region recorded the highest sales and profit.
- Some high-sales customers also generated losses.
- Discount and profit showed a weak negative correlation of -0.216.

## Dashboard

The project includes a dashboard containing six visualisations:

![Superstore Sales Dashboard](Images/sales_dashboard.png)

## Data Cleaning
- Checked missing values.
- Checked duplicate records.
- Inspected data types.
- Identified future-dated transactions.
- Excluded future-dated transactions from historical analysis.

The historical analysis contains 9,483 records and excludes 711 future-dated records.

## Conclusion
This project demonstrates how Python can be used for data cleaning, exploratory data analysis, visualisation, and business insight generation.

The findings highlight opportunities to improve product profitability, review discount strategies, and monitor customer performance.

## Author
BSc Data Science Student | Aspiring Data Analyst
## Conclusion

This project demonstrates the use of Python for analysing retail sales data and extracting meaningful business insights.

Through data cleaning, exploratory data analysis, customer analysis, regional performance analysis, and data visualization, the project identifies important sales and profitability trends.

The analysis highlights the relationship between discounts and profitability and identifies profitable and loss-making product sub-categories.

This project helped strengthen my practical skills in Python, Pandas, NumPy, Matplotlib, Seaborn, and data-driven business analysis.
