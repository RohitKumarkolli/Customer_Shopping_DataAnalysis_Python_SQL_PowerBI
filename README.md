📊 Customer Shopping Behavior Analysis
📘 Overview

This project analyzes customer shopping behavior using a dataset of 3,900 transactions. The goal is to understand spending patterns, customer demographics, product performance, and subscription preferences through data analysis, SQL, and an interactive dashboard.

The workflow includes:

Loading and cleaning data in Python

Exploratory Data Analysis (EDA)

Running SQL queries in PostgreSQL

Building an interactive Power BI dashboard

Creating a final business insights report using Gamma

📂 Dataset Summary

Rows: 3,900

Columns: 18

Types of Data:

Customer demographics (age, gender, location, subscription status)

Purchase details (category, item, amount, season, size, color)

Behavioral data (discount applied, previous purchases, ratings)

Missing Values:

37 missing values in Review Rating column

🧰 Tools & Technologies

Python – Pandas, NumPy, Matplotlib, Seaborn

PostgreSQL – SQL queries for deeper analysis

Power BI – Dashboard and data visualization

Gamma.app – Final project report

Git/GitHub – Version control

🛠 Project Steps
1. Data Loading & EDA (Python)

Loaded dataset using pandas

Explored dataset using .info(), .describe(), and visualizations

Detected missing values and outliers

2. Data Cleaning

Imputed missing review ratings using median per category

Standardized column names

Converted shopping frequency values to numeric

Created new features (ex: age groups)

Removed redundant features

Uploaded cleaned dataset to PostgreSQL

3. SQL Analysis (PostgreSQL)

Performed structured queries to answer business questions such as:

Revenue by gender

Discount users vs non-discount users

Top-rated products

Revenue comparison: standard vs express shipping

Subscribed vs unsubscribed customer behavior

Customer segmentation (new, returning, loyal)

Most purchased products by category

Repeat buyers likely to subscribe

Revenue by age groups

4. Power BI Dashboard

Created a dashboard that visualizes:

Sales trends

Customer demographics

Category performance

Subscription patterns

Discount usage

Rating insights

5. Final PPT Report (Gamma)

A clean, presentation-ready report summarizing findings, insights, and recommendations.

📈 Key Results

Female customers generated slightly higher revenue

Loyal and subscribed customers spend more frequently

Discounts drive higher purchase counts



Express shipping correlates with higher order value

Middle-aged groups contribute the highest revenue

Several top-rated items show strong repeat purchase behavior


<img width="1078" height="611" alt="image" src="https://github.com/user-attachments/assets/5b85f214-45aa-487c-800a-25c20351da38" />
