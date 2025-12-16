# Retail Customer Behavior Analysis — Data Analytics Portfolio Project
**Data Analysis Project | Python • SQL • Power BI**

This project analyzes customer shopping behavior for a retail company to uncover trends, understand customer loyalty, and identify key factors influencing purchasing decisions.  
The analysis focuses on **data cleaning, feature engineering, exploratory data analysis using SQL**, and preparing a finalized dataset for **Power BI dashboards**.

---

## Business Problem
A retail company wants to better understand its customers’ shopping behavior in order to improve:

- Sales performance  
- Customer engagement  
- Loyalty and subscription strategies  
- Product and marketing decisions  

Management observed changes in purchasing patterns across demographics, product categories, and customer segments and seeks data-driven insights.

---

## Dataset
The original dataset `customer_shopping_behavior.csv` contains **3900 customer transactions**, including:

- Customer demographics (age, gender, location)
- Product details (item purchased, category, size, color, season)
- Purchase behavior (purchase amount, discounts, shipping type)
- Loyalty indicators (previous purchases, purchase frequency)
- Subscription status and payment methods

---

## Data Preparation & Feature Engineering (Python)
Data processing was performed using **Pandas** in Jupyter Notebook:

- Standardized column names (lowercase, snake_case)
- Handled missing values in `review_rating` using category-level medians
- Removed redundant features
- Created engineered features:
  - `age_group` — customer life-stage segmentation
  - `frequency_of_purchases_days` — numerical representation of purchase frequency

A clean and stable dataset was prepared for analysis and reporting.

---

## Exploratory Data Analysis (EDA using SQL)
The cleaned dataset was loaded into a SQLite database using **SQLAlchemy**.  
All analytical questions were answered using **SQL queries**, including:

- Revenue comparison by gender
- Impact of discounts on spending behavior
- Customer loyalty and repeat purchases
- Top products by sales volume and review ratings
- Subscription behavior and spending patterns
- Revenue contribution by age group
- Product performance within each category

This phase demonstrates professional use of SQL for business-driven data analysis.

---

## Final Data Export
A finalized and locked version of the dataset was created for business intelligence and reporting:

- **CSV File**: `customer_transactions_final.csv`
- **SQLite Database**: `retail_final.db`
  - Table: `customer_transactions_final`

These files are ready for direct use in **Power BI**.

---

## Visualization & Dashboard (Power BI)
The final CSV dataset is used to build interactive dashboards in **Power BI**, highlighting:

- Customer segments and revenue contribution
- Product and category performance
- Loyalty and subscription insights
- Discount usage patterns

The dashboards enable stakeholders to explore insights and support data-driven decisions.

---

## How to Run
1. Open `Retail_Customer_Behavior_Analysis.ipynb` in **Jupyter Notebook**
2. Place `customer_shopping_behavior.csv` in the same directory
3. Run all cells sequentially
4. The final datasets will be generated:
   - `customer_transactions_final.csv`
   - `retail_final.db`

---

## Key Skills Demonstrated
- Data Cleaning & Feature Engineering (Python / Pandas)
- Exploratory Data Analysis using SQL
- Business-oriented analytical thinking
- Data preparation for BI tools
- End-to-end data analysis workflow

---

## Author
**Qusay — Data Analytics / Data Science Portfolio Project**

🔗 LinkedIn: https://www.linkedin.com/in/qusay-alhasanat  
🔗 GitHub: https://github.com/Qusay-Alhasanat  
📧 Email: qusay.alhasanat1@gmail.com
