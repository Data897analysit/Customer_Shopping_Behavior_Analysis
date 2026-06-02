# Customer_Shopping_Behavior_Analysis
Retail customer shopping behavior analysis using Python (EDA), PostgreSQL (SQL queries), and Power BI (dashboard) on 3,900 customer records to uncover revenue patterns, segments, and business insights.

Overview

This project demonstrates a full data analytics pipeline applied to a real-world business dataset. The goal was to extract meaningful insights from raw data and present them in a way that supports business decision-making.

The workflow covers every stage an analyst handles on the job — from messy raw data to a polished stakeholder presentation — making it a practical showcase of both technical and communication skills.

🗂️ Dataset

Property Detail Format CSV Loaded via Python (Pandas)Key areas covered Demographics, transactions, behavior, ratings
The dataset was loaded, inspected, and cleaned before any analysis was performed.

🛠️ Tools & Technologies

ToolRole in ProjectPython (Pandas)Data loading, cleaning, EDAPostgreSQLStructured querying and business analysis Power BI Interactive dashboard Microsoft PowerPoint Stakeholder presentation Jupyter Notebook Development environment

🔄 Project Steps
Step 1 — Load & Inspect Data (Python)

Imported dataset using pandas

Used df.info(), df.describe(), and df.shape to understand structure

Identified column types, row counts, and initial data quality issues

Step 2 — Data Cleaning (Exploratory Data Analysis -Python)

Detected and handled missing values using df.isnull().sum()

Imputed nulls using median values grouped by relevant categories

Standardized column names to lowercase with underscores

Removed duplicate or redundant columns

Created new features through feature engineering (binning, derived columns)


Step 3 — SQL Analysis (PostgreSQL)

Imported the cleaned dataset into a PostgreSQL database

Wrote queries to answer specific business questions:

Revenue breakdown by category and demographics

Customer segmentation (Loyal, Returning, New)

Top-rated products and discount-dependent items

Subscriber vs non-subscriber spend comparison

Shipping type performance



Step 4 — Dashboard (Power BI)

Connected Power BI to the cleaned dataset

Built an interactive dashboard with slicers for dynamic filtering

Included KPI cards, bar charts, donut charts, and trend visuals

Step 5 — Report & Presentation

Compiled findings into a structured PDF report

Created a PowerPoint presentation tailored for stakeholders

Focused on insights and recommendations — not just charts


📊 Dashboard Highlights

The Power BI dashboard includes:

KPI Cards — Total customers, average purchase amount, average review rating

Revenue by Category — Clustered bar chart showing category-level performance

Revenue by Age Group — Horizontal bar chart segmented by age

Subscription Split — Donut chart (Subscribers vs Non-subscribers)

Sales by Category — Volume comparison across product types

Slicers — Filter by gender, subscription status, category, and shipping type


📈 Key Results

Identified the top-performing product category driving the majority of revenue

Found that loyal customers make up the largest customer segment

Discovered express shipping users have a higher average spend

Revealed which products are most dependent on discounts to drive purchases

Uncovered that subscriber and non-subscriber spending is nearly identical — signaling an opportunity to add more subscription value


💡 Recommendations Delivered

Launch a premium subscription tier to convert non-subscribers


Build a loyalty rewards program targeting the largest customer segment
Promote top-rated products in marketing campaigns


Use age and shipping preference data for targeted advertising


📬 Contact

Name: - Priyanshi

📧 priyanshi1652001@gmail.com

🔗Linkedin Profile: - https://www.linkedin.com/in/priyanshi-rajput

💻Github Profile: - https://github.com/Data897analysit

