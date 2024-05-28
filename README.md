# Data Analyst Project - Sales Performance Analysis

[Sales Dashboard](https://public.tableau.com/views/Salesdashboard_17168646680020/SalesOverview?:language=zh-TW&:sid=&:display_count=n&:origin=viz_share_link)

## Business requirement Overview
Stakeholder: Sales Manager 

<img width="651" alt="Screenshot 2024-05-28 at 12 01 56 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/5c9bad1d-f754-41ed-92fa-9867ca463ce6">

<img width="652" alt="Screenshot 2024-05-28 at 12 02 15 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/8acb8a3c-6ad0-4255-a59e-867c8c6db7af">

## Data Model
In data modeling, I identified the Sales Orders table as the fact table and Product, Customer, Calendar, and KPI Target Value as dimension tables. I defined primary keys (PK) for each table and established foreign key (FK) relationships from the fact table to each dimension table, indicating many-to-one relationships. An Entity-Relationship Diagram (ERD) was created to visualize these connections. Finally, I built a star schema, with the central fact table linked to surrounding dimension tables, ensuring efficient data organization for analysis and reporting.

- Fact table: SalesOrders
- Dimension table: Products, Customers, Calendars, Target_Gross_Margin(KPI), Target_Sales(KPI)
<img width="796" alt="Screenshot 2024-05-27 at 3 13 44 PM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/4580a40b-1d40-4ccc-a970-8016abffeeb1">

## Data Cleaning & Data Transformation(SQL)

To create the necessary data model for doing data analysis and fulfilling the business needs defined in the business requirement the following tables were extracted using SQL

## Dashboard
[Try it out!](https://public.tableau.com/views/Salesdashboard_17168646680020/SalesOverview?:language=zh-TW&:sid=&:display_count=n&:origin=viz_share_link)
The finished Sales Performance Dashboard has three pages 
- Sales overview
  <img width="1010" alt="Screenshot 2024-05-28 at 12 06 03 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/d98bce5d-fa4f-40c4-a58b-54fa218bc684">

- Products Detail
  <img width="1010" alt="Screenshot 2024-05-28 at 12 06 14 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/00a3fad1-56b0-46fe-81d9-b9f27a635821">

- Customers Detail
  <img width="1009" alt="Screenshot 2024-05-28 at 12 06 24 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/d951806f-7459-4248-a1a7-dc81ee24e691">

