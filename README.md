# Customer Marketing Analysis with Python

## Overview

This project analyzes customer demographics, purchasing behavior, spending patterns, and marketing campaign performance using Python.

The objective is to demonstrate how Python can be used to clean and transform real-world data, perform exploratory data analysis (EDA), create meaningful visualizations, and translate findings into business insights.

---

## Business Objective

The analysis aims to answer four key questions:

- Who are the company's customers?
- How is customer spending distributed?
- Which purchasing channels are used most frequently?
- How have previous marketing campaigns performed?

---

## Dataset

The project uses the **Customer Personality Analysis / Marketing Campaign** dataset.

The dataset contains **2,240 customers** and includes information about:

- Customer demographics
- Income and household characteristics
- Product spending
- Purchasing channels
- Previous marketing campaign acceptance
- Latest campaign response

### Main Variables

| Category | Examples |
|---|---|
| Demographics | Age, Education, Marital Status |
| Household | Kidhome, Teenhome |
| Spending | Wines, Fruits, Meat, Fish, Sweets, Gold |
| Purchasing Channels | Web, Catalog, Store |
| Marketing | AcceptedCmp1–5, Response |
| Customer Activity | Recency, Web Visits, Deals Purchases |

---

## Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## Project Workflow

### 1. Data Understanding

The dataset was examined to understand:

- Dataset dimensions and structure
- Data types
- Missing values
- Duplicate records
- Categorical variables
- Numerical distributions
- Potential data-quality issues

### 2. Data Cleaning

The following data-quality issues were addressed:

- Missing income values
- Unrealistic birth years
- An extreme income value
- Rare and inconsistent marital-status categories
- Date formatting
- Constant columns with no analytical value

### 3. Feature Engineering

Several useful features were created:

- `Age`
- `Age_Group`
- `Total_Spending`
- `Total_Purchases`
- `Total_Children`
- `Spending_Segment`

### 4. Exploratory Data Analysis

The analysis examined:

- Customer age distribution
- Education distribution
- Marital-status distribution
- Customer spending distribution
- Purchasing channels
- Marketing campaign acceptance rates

### 5. Business Insights

The analysis was translated into concise business findings rather than focusing only on technical results.

---

## Key Findings

### Customer Demographics

Customers aged **30–49** represent approximately **55%** of the customer base, making this the core age group in the dataset.

### Education

**Graduation** is the most common education level among customers, followed by **PhD** and **Master**.

### Marital Status

**Married** customers represent **38.6%** of the customer base, followed by **Together** at **25.9%**.

Combined, these groups account for **64.5%** of customers.

### Purchasing Channels

Store purchases are the most common purchasing channel:

| Channel | Share |
|---|---:|
| Store | 46.2% |
| Web | 32.6% |
| Catalog | 21.2% |

### Marketing Campaigns

Campaign 4 achieved the highest acceptance rate among the five previous campaigns at **7.5%**, while Campaign 2 had the lowest at **1.3%**.

The latest campaign had an overall response rate of **14.9%**.

### Spending Distribution

Customer spending is strongly **right-skewed**, with most customers concentrated at lower spending levels and a smaller group spending substantially more.

---

## Python Skills Demonstrated

This project demonstrates practical Python skills relevant to an entry-level Data Analyst role.

### Data Manipulation & Cleaning

- Loading data with Pandas
- DataFrame inspection
- Missing-value analysis
- Duplicate detection
- Conditional transformations
- Categorical data cleaning
- Datetime conversion
- Column selection and manipulation

### Feature Engineering

- Creating calculated columns
- Aggregating multiple columns
- Creating categorical age groups
- Quantile-based segmentation

### Data Analysis

- Descriptive statistics
- `value_counts()`
- `groupby()`
- Percentage calculations
- Distribution analysis

### Data Visualization

- Bar charts
- Horizontal bar charts
- Pie charts
- Histograms
- Chart labeling and formatting

### Business Analysis

- Identifying customer demographic patterns
- Understanding purchasing behavior
- Evaluating campaign performance
- Translating analytical results into business insights

---

## Project Structure

```text
customer-marketing-analysis-python/
│
├── data/
│   └── marketing_campaign.csv
│
├── notebooks/
│   └── customer_marketing_analysis.ipynb
│
└── README.md

