#  Supermarket Sales Analysis Using Python

**End-to-End Data Analytics Project using Python**

#  Project Overview

- This project focuses on analyzing supermarket sales data to understand sales performance, customer purchasing behavior, product line performance, and payment preferences.
- It demonstrates an end-to-end Data Analytics workflow, including data loading, data cleaning, exploratory data analysis (EDA), data visualization, and business insight generation using Python.
- The project uses transaction-level sales data to explore patterns and trends that can help improve business decisions.

#  Project Objectives

- Load and understand supermarket sales data
- Identify numerical and categorical columns
- Check and handle missing values and duplicate records
- Perform Exploratory Data Analysis (EDA)
- Analyze sales performance across product lines
- Explore customer purchasing behavior and payment preferences
- Visualize data using Matplotlib and Seaborn
- Generate meaningful business insights and recommendations

#  Skills & Tools Used (ATS Optimized)

- Python
- NumPy
- Pandas
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Matplotlib
- Seaborn
- Data Interpretation
- Business Analytics

#  Dataset Information

**Dataset Name:** Supermarket Sales Dataset  
**Target Variable for Sales Analysis:** `Total`

**Key Features:**

**Transaction Information:**
- `Invoice ID`
- `Branch`
- `City`
- `Date`
- `Time`

**Customer Information:**
- `Customer type`
- `Gender`

**Product Information:**
- `Product line`
- `Unit price`
- `Quantity`

**Sales & Profit Information:**
- `Tax 5%`
- `Total`
- `cogs`
- `gross margin percentage`
- `gross income`

**Payment & Customer Feedback:**
- `Payment`
- `Rating`

The dataset contains transaction-level information about supermarket sales, products, customers, payment methods, and gross income.

#  Project Workflow

## 1️. Data Loading & Understanding

- Loaded the dataset using Pandas.
- Checked the number of rows and columns using `shape`.
- Inspected column names and data types.
- Used summary statistics to understand numerical data.
- Identified numerical and categorical columns.

## 2️. Data Cleaning & Preprocessing

- Checked for missing values using `isnull().sum()`.
- Checked for duplicate records using `duplicated().sum()`.
- Verified data types and identified potential inconsistencies.
- Converted the `Date` column to datetime format for time-based analysis, if required.
- Handled data quality issues based on the results of the checks.

## 3️. Exploratory Data Analysis (EDA)

**EDA was performed using:**
1. Summary statistics
2. GroupBy analysis
3. Aggregation functions
4. Correlation analysis
5. Data visualization

**Key Analysis Areas:**
1. Total sales by product line
2. Monthly sales trends
3. Payment method distribution
4. Unit price distribution
5. Relationship between quantity and total sales
6. Gross income across product lines

## 4️. Data Visualization

**Visualizations were created using Matplotlib and Seaborn:**

1. **Bar Chart:** Analyze total sales across product lines.
2. **Line Chart:** Examine monthly sales trends.
3. **Pie Chart:** Understand the distribution of payment methods.
4. **Histogram:** Explore the distribution of unit prices.
5. **Scatter Plot:** Analyze the relationship between quantity and total sales.
6. **Box Plot:** Compare gross income across product lines.

These visualizations help present sales patterns and customer purchasing behavior in an easy-to-understand format.

## 5️. Sales & Product Analysis

- Analyzed total sales across different product lines.
- Compared product category performance.
- Examined transaction quantities and unit prices.
- Identified product categories contributing to overall sales.
- Studied gross income across different product lines.

## 6️. Customer & Payment Analysis

**Customer and transaction patterns were explored across:**
- Customer types
- Gender
- Payment methods
- Branches and cities
- Customer ratings

This analysis helps understand customer preferences, transaction behavior, and differences in sales performance across locations.

## 7️. Key Business Insights

The following insights can be investigated using the dataset:

1. Identify the product line with the highest total sales.
2. Determine which months show higher or lower sales.
3. Identify the most frequently used payment method.
4. Compare gross income across product lines.
5. Examine the relationship between quantity purchased and total sales.
6. Compare sales performance across branches and cities.


##  Business Recommendations

1. Focus on product lines that contribute significantly to total sales.
2. Use monthly sales trends to support inventory and sales planning.
3. Consider customer payment preferences when improving the checkout experience.
4. Compare branch performance to identify opportunities for improvement.
5. Monitor customer ratings to identify areas where customer satisfaction may be improved.
6. Use gross income analysis to support product and business performance decisions.

#  Limitations & Assumptions

**Limitations:**

- The dataset covers a limited period and may not represent long-term sales trends.
- The analysis describes patterns and relationships but does not prove causation.
- The dataset does not include detailed marketing costs or all operating expenses.
- The analysis does not include predictive modeling or future sales forecasting.

**Assumptions:**

- The recorded transactions accurately represent the sales included in the dataset.
- The `Total` column represents the total transaction amount.
- The `gross income` column is used as the available measure of gross income, not overall net profit.

#  Conclusion

This project demonstrates the use of Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to analyze supermarket sales data. Through data cleaning, exploratory data analysis, and visualization, the project explores sales performance, product line trends, customer behavior, payment preferences, and gross income.

The findings can help businesses better understand sales patterns and make data-informed decisions about inventory, product performance, and customer experience.



