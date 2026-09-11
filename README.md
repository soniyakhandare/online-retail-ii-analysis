# Online Retail II — The Story Behind the Transactions

## Project Overview

This project analyzes the Online Retail II dataset using Python to clean, explore, analyze, and visualize transactional data.

The project follows a complete data analysis workflow:

**Raw Data → Data Cleaning → Exploratory Data Analysis → Outlier Detection → Visualization → Insights**

The analysis compares two periods:

- 2009–2010
- 2010–2011

## Dataset

The Online Retail II dataset contains transactional records from a UK-based online retailer.

It includes information such as:

- Invoice
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Price
- Customer ID
- Country

Source: UCI Machine Learning Repository

## Data Cleaning

The dataset was cleaned using Python and Pandas.

The preprocessing included:

- Removing duplicate records
- Identifying cancelled transactions
- Identifying accounting adjustments
- Removing invalid or zero-price transactions
- Removing invalid or negative quantities
- Checking missing values
- Creating a `TotalAmount` variable
- Checking and identifying outliers using the IQR method

Extreme values were retained where they could represent genuine high-value or high-quantity transactions.

## Analysis Performed

The project explores:

- Overall sales comparison
- Monthly sales trends
- Country-wise sales
- Product-wise quantity sold
- Customer spending
- Day-of-week sales patterns
- Outlier analysis

## Key Insights

1. Overall revenue increased between the two periods.
2. Average customer spending increased in 2010–2011.
3. The UK was the dominant market in terms of sales.
4. A small group of products contributed significantly to total quantity sold.
5. Sales showed noticeable patterns across different months and days of the week.

## Visualizations

Python-generated visualizations were used to communicate the findings, including:

- Bar charts
- Line charts
- Boxplots
- Pie charts
- Year-over-year comparisons

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
online-retail-ii-analysis/
│
├── notebooks/
│   └── Python_DDA_Project.ipynb
│
├── presentation/
│   └── Online_Retail_II_Data_Storytelling_Insights.pptx
│
└── README.md

## Conclusion 
 
This project demonstrates how raw transactional data can be transformed into meaningful business insights through systematic data cleaning, exploratory analysis, visualization, and data storytelling. 
 
The analysis was performed using Python and documented in a Jupyter Notebook. The presentation summarizes the key findings and insights from the analysis.
