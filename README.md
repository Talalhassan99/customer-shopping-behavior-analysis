# customer-shopping-behavior-analysis
End-to-end customer shopping behavior analysis using Python, PostgreSQL, SQL and Power BI.

## Project Overview

This project analyzes customer shopping behavior using transactional data to identify spending patterns, customer segments, product preferences, discount behavior, and subscription trends.

The project follows an end-to-end analytics workflow:

Raw Data → Python/Pandas → PostgreSQL → SQL Analysis → Power BI Dashboard

## Dataset

- 3,900 customer purchase transactions
- 18 columns
- Customer demographics
- Purchase details
- Shopping behavior
- Subscription information
- Product and shipping information

## Tools & Technologies

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI
- DAX
- Excel

## Project Workflow

### 1. Data Cleaning & Preparation

Python and Pandas were used to:

- Explore the dataset
- Handle missing values
- Standardize column names
- Create age groups
- Create purchase-frequency features
- Validate discount and promotional-code consistency
- Prepare the cleaned dataset for PostgreSQL

### 2. SQL Analysis

SQL was used to analyze:

- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Shipping type performance
- Subscribers vs non-subscribers
- Discount-dependent products
- Customer segmentation
- Top products by category
- Repeat buyers and subscription behavior
- Revenue by age group

### 3. Power BI Dashboard

The cleaned and analyzed data was visualized through an interactive Power BI dashboard.

Key areas include:

- Customer overview
- Revenue by category
- Subscription behavior
- Age-group analysis
- Product performance
- Customer segmentation
- Shipping analysis
- Discount analysis

## Business Recommendations

The analysis provides insights into:

- Subscription opportunities
- Customer loyalty
- Discount dependency
- Product positioning
- Targeted marketing


## Project Structure

```text
customer-shopping-behavior-analysis/
│
├── README.md
├── notebooks/
│   └── customer_shopping_behavior_analysis.ipynb
├── sql/
│   └── customer_analysis.sql
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
├── data/
│   └── README.md
