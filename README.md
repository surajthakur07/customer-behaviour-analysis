# customer-behaviour-analysis
An end-to-end data analytics project analyzing 3,900 retail transactions to uncover customer shopping behavior. Features data cleaning in Python , business analysis in SQL , and an interactive Power BI dashboard to optimize marketing strategies.
# Customer Shopping Behavior Analysis

## Project Overview
[cite_start]This project analyzes transactional data from 3,900 purchases to uncover insights into customer spending patterns, product preferences, and subscription behavior[cite: 16, 17]. [cite_start]The objective is to help a retail company leverage consumer data to identify trends, improve customer engagement, and optimize both marketing and product strategies[cite: 6].

## Dataset Summary
* [cite_start]**Size:** 3,900 rows and 18 columns[cite: 19, 20].
* [cite_start]**Features:** Includes customer demographics (age, gender, location), purchase details (amount, category, season), and shopping behavior (discounts, review ratings, shipping type)[cite: 22, 23, 24].

## Tech Stack & Workflow
1. [cite_start]**Python (Data Preparation):** Cleaned the raw data using pandas, handled missing values by imputing the median for review ratings, and engineered new features like `age_group` and `purchase_frequency_days`[cite: 8, 28, 32, 35, 36].
2. [cite_start]**PostgreSQL (Data Analysis):** Loaded the cleaned dataset into a database and executed SQL queries to segment customers (New, Returning, Loyal), compare shipping types, and analyze revenue by demographics and subscription status[cite: 38, 40, 57, 60, 66].
3. [cite_start]**Power BI (Visualization):** Developed a dashboard to track key metrics such as average purchase amount, revenue by age group, and sales by product category[cite: 10, 89, 90].

## Key Business Recommendations
* [cite_start]**Targeted Marketing:** Focus promotional efforts on high-revenue age groups and customers utilizing express shipping[cite: 134].
* [cite_start]**Boost Subscriptions:** Promote exclusive benefits to convert non-subscribers[cite: 128].
* [cite_start]**Loyalty Programs:** Incentivize repeat buyers to transition them into the "Loyal" customer segment[cite: 131].
* [cite_start]**Product Positioning:** Highlight top-rated and best-selling products in upcoming campaigns[cite: 133].
