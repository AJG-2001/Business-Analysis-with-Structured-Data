Business Analysis with Structured Data 

📌 Project Overview

This project analyzes the performance of a large e-commerce platform dataset (Mercado Livre) using AWS RDS, SQL queries, Python, and Amazon QuickSight. The assignment’s purpose was to demonstrate proficiency in cloud database services, ETL processes, and business analytics storytelling.

Deliverables included:

SQL scripts used for data transformation and analysis.

A PDF presentation report and supporting documentation.

🔎 ETL & Data Preparation

Uploaded original SQL datasets into AWS RDS.

Cleaned and standardized multiple tables (orders, items, payments, products, and marketing).

Replaced generic headers (C1, C2) with meaningful column names.

Created a transformed orders table (T_Orders) including a status column:

Complete: delivered or shipped.

Incomplete: pending, canceled, or undefined.

Standardized marketing origins, replacing null and “other” with unknown.

Joined multiple datasets (payments, geolocation, customer demographics) to enrich analysis
.

📊 Business Analysis & Insights
1. Marketing Channels

Top three channels: Organic Search, Paid Search, and Unspecified, accounting for ~66% of all leads
.

Recommendation: scale up social media campaigns (e.g., Instagram, TikTok) and refine email marketing for higher conversion
.

2. Operations

Payment Methods: Credit cards dominate (~74% of transactions).

Delivery Speed: Faster deliveries correlated with higher revenue and retention.

Reviews:

7,202 reviews collected with an average rating of 4.1/5.

77% were positive (4–5 stars).

Categories like construction tools and electronics scored highest
.

3. Sales & Revenue

Geographic Reach: 87% of sales concentrated in São Paulo, Minas Gerais, and Rio de Janeiro, Brazil’s wealthiest states.

Top Products: Bed & Bath, Telephony, Sports/Leisure, and Furniture/Decor.

Revenue Trends:

Best months: October & November (holiday spike).

Slight dip in December, followed by steady growth Jan–Apr, suggesting successful customer retention
.

Correlation: Expensive furniture had lower review scores, reflecting higher consumer expectations.

🗂️ Deliverables

A2_Assignment_BusinessAnalysis.pdf – Business report presentation.

A2_Assignment_Canvas.pdf – Visual presentation slides.

A2_Assignment_SQL_Code.txt – SQL queries for data transformation and insights.

README.md – Project overview (this file).

🎥 YouTube Video Presentation
.

🚀 Key Takeaways

AWS RDS & SQL: Cloud-based ETL pipelines enabled scalable, collaborative data analysis.

QuickSight & Python: Provided intuitive visualizations and geospatial insights.

Business Findings:

Focus marketing on organic and social media channels.

Optimize delivery logistics to improve revenue and satisfaction.

Increase inventory and bundles in top product categories (electronics, home goods).

Demonstrated how structured data analysis supports data-driven decision making for e-commerce growth.
