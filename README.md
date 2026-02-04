# Walmart Sales Analysis

## Project Overview
This project focuses on exploratory data analysis (EDA) of Walmart retail transaction data to understand sales patterns and identify key factors influencing revenue across branches, time periods, and product categories.

The analysis aims to provide business insights that can help improve operational and sales strategies.

---

## Dataset Description
- Source: Walmart Sales Dataset (Kaggle)
- Each row represents a single customer transaction.
- Key attributes include:
  - Branch and City
  - Product category
  - Date and Time of purchase
  - Quantity, Unit price, and Total bill
  - Customer type and Gender

---

## Objectives
- Compare sales performance across different branches
- Analyze customer purchasing behavior across time periods
- Understand the impact of weekdays vs weekends on sales
- Identify whether higher sales are driven by transaction volume or average bill value

---

## Feature Engineering
To make the data more interpretable for business analysis, the following features were derived:
- **Day Type**: Weekday or Weekend (from Date)
- **Time of Day**: Morning, Afternoon, Evening (from Time)
- **Average Transaction Value**: Derived from total bill amounts

---

## Exploratory Data Analysis
The following analyses were performed:
- Branch-wise total sales comparison
- Transaction volume and revenue comparison
- Weekend vs weekday sales analysis
- Time-of-day sales distribution
- Product category contribution to revenue

Visualizations such as bar charts and distribution plots were used to identify trends and patterns.

---

## Key Insights
- Sales performance varies significantly across branches
- Weekends and afternoon hours tend to show higher sales
- High-performing branches benefit from both higher transaction volume and higher average bill values
- Sales differences are driven by multiple interacting factors rather than a single variable

---

## Limitations
- Customer-level repeat behavior could not be analyzed due to lack of unique customer IDs
- Product data is available only at category level, not individual SKU level
- Analysis is descriptive and does not include predictive modeling

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib & Seaborn for visualization
- Jupyter Notebook

---

## Conclusion
This project demonstrates how exploratory data analysis can uncover actionable insights from retail transaction data and support data-driven decision-making in a business context.
