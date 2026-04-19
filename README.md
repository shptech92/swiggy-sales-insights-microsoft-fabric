# Swiggy Sales Insights Dashboard | Microsoft Fabric Project

## Project Overview

This project focuses on analyzing Swiggy food delivery data using Microsoft Fabric and Power BI to identify key business insights related to revenue performance, customer preferences, and location-based demand patterns.

The objective of this project is to transform raw transactional data into meaningful insights that can support better business decision-making and improve profitability.

The dashboard provides a clear understanding of ordering behaviour, top-performing restaurants, popular food categories, and revenue contribution across different locations.

---

## Business Problem

Food delivery platforms operate in a highly competitive market where understanding customer behaviour and demand patterns is important for increasing revenue and improving customer experience.

This project helps answer key business questions:

• Which restaurants generate the most revenue?
• Which food category is most preferred by customers?
• Which locations contribute highest sales?
• How does order demand vary across months and days?
• What factors influence average order value?

---

## Dataset Description

The dataset follows a star schema model with one fact table and multiple dimension tables.

Fact Table:

fact_orders  
Contains transactional order-level data such as order amount, quantity, rating, and date reference.

Dimension Tables:

dim_date  
Provides order date details for time-based analysis.

dim_dish  
Contains dish and food category information.

dim_restaurant  
Includes restaurant names and related attributes.

dim_location  
Provides location and state-level data.

---

## Data Model

The project uses a star schema model to ensure efficient querying and analysis.

Relationships:

dim_date → fact_orders  
dim_dish → fact_orders  
dim_restaurant → fact_orders  
dim_location → fact_orders  

This structure helps in analyzing sales across multiple dimensions like time, restaurant, food category, and location.

---

## Tools & Technologies Used

Microsoft Fabric  
Power BI  
Data Modeling  
DAX  
Data Visualization  
ETL Concepts  
Business Intelligence  

---

## Dashboard KPIs

Total Sales: ₹53.01M  
Total Orders: 197K  
Average Order Value: ₹268.51  
Average Rating: 4.34  
Total Ratings Count: 5.59M  

---

## Key Business Insights

• Generated ₹53M revenue across 197K orders, showing strong and consistent demand.

• Veg food contributes 63.7% of total revenue (₹33.77M), indicating higher customer preference compared to non-veg items.

• Top brands like KFC (₹4.2M), McDonald's (₹3.3M), and Pizza Hut generate significant revenue share, highlighting strong brand influence on ordering behaviour.

• Karnataka recorded highest revenue contribution of ₹5.5M, indicating strong demand concentration in specific regions.

• Monthly sales trend remains stable between ₹6.2M and ₹6.8M, showing consistent ordering patterns.

• Weekend orders are slightly higher, with Saturday recording highest sales (~₹7.8M), indicating behavioural demand patterns.

• Average order value of ₹268 suggests opportunity to increase revenue through combo offers and upselling strategies.

• Customer satisfaction remains strong with an average rating of 4.34 across 5.59M ratings.

---

## Business Value

The insights generated from this dashboard can help businesses:

Improve promotional strategy  
Identify high-performing restaurant partners  
Understand customer food preferences  
Optimize location-based marketing campaigns  
Increase average order value  
Support data-driven decision making  

---

## Project Learnings

Through this project, I gained practical experience in:

Designing star schema data models  
Building interactive dashboards in Power BI  
Using DAX to create calculated measures  
Identifying trends and patterns in transactional data  
Converting raw data into actionable business insights  
Understanding how analytics supports business decisions  

---

## Project Structure

Swiggy-Microsoft-Fabric-Project

Dataset  
dim_date.csv  
dim_dish.csv  
dim_location.csv  
dim_restaurant.csv  
fact_orders.csv  

Dashboard  
Swiggy_Report.pbix  
Dashboard_Screenshot.png  

Documentation  
Data_Model.png  

README.md

---

## Future Improvements

Customer segmentation analysis  
Delivery performance analysis  
Predictive demand forecasting  
Customer lifetime value analysis  

---

## Author

 Data Analyst skilled in Microsoft Fabric, Power BI, Data Modeling, and Business Intelligence concepts.
