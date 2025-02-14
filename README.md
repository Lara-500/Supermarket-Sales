# Supermarket Sales Analysis

## Project Overview
This project analyzes supermarket sales data to extract meaningful insights using data wrangling and visualization techniques. The dataset includes sales transactions from different branches, tax details, customer ratings, and other key metrics. The goal is to identify trends, correlations, and business opportunities to enhance decision-making.

## Dataset Information
- **Source:** Supermarket Sales Dataset
- **Size:** Multiple columns and rows capturing sales transactions
- **Key Features:**
  - **Branch:** Store location (Yangon, Naypyitaw, Mandalay)
  - **Quantity:** Number of items purchased per transaction
  - **Tax 5%:** Tax applied on sales
  - **Total:** Total amount spent per transaction
  - **Rating:** Customer rating (1-10 scale)
  - **Date & Time:** Purchase timestamp for time-based analysis

## Data Wrangling Steps
- **Handled missing values** (Checked for null values and ensured data consistency)
- **Removed duplicates** to maintain data integrity
- **Standardized formats** for date and numerical columns
- **Created new features** (e.g., extracting month/day from the date column for better time-based insights)

## Data Analysis & Insights
### 1️⃣ Feature Correlation Heatmap
- Strong positive correlation between **Tax 5%** and **Total** (0.98), confirming tax is directly proportional to total sales.
- Moderate correlation between **Quantity and Total (0.7)**, showing higher quantities lead to higher sales.
- No significant correlation between customer **Rating** and sales performance.

### 2️⃣ Branch Performance Analysis
- **Yangon, Naypyitaw, and Mandalay** show different sales patterns.
- Naypyitaw has a **negative correlation with Mandalay (-0.49)**, suggesting branch performance varies significantly.

### 3️⃣ Time-Based Trends
- Monthly and daily trends reveal variations in purchase behavior.
- Sales fluctuate based on **days of the month**, which can be useful for targeted promotions.

## Business Recommendations
- **Increase promotions on high-demand items** to maximize revenue.
- **Monitor sales fluctuations by branch** and optimize stock levels accordingly.
- **Improve customer engagement strategies**, as ratings do not strongly impact sales.
- **Implement time-based discounts** during slow sales periods to boost revenue.

## Tools & Technologies Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** for data processing & visualization
- **Google Colab** for analysis
- **GitHub** for version control and collaboration
