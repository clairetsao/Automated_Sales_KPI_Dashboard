# Data Analyst Project - Sales Performance Analysis

[Sales Management Dashboard](https://public.tableau.com/views/Salesdashboard_17168646680020/SalesOverview?:language=zh-TW&:sid=&:display_count=n&:origin=viz_share_link)

## Project Description
This project involves creating a comprehensive Sales Performance Dashboard to assist the Sales Manager in monitoring and analyzing sales data. The dashboard provides insights into key sales metrics, helping to make informed decisions to drive business growth.

## Business requirement Overview
Stakeholder: Sales Manager 

<img width="651" alt="Screenshot 2024-05-28 at 12 01 56 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/5c9bad1d-f754-41ed-92fa-9867ca463ce6">

<img width="652" alt="Screenshot 2024-05-28 at 12 02 15 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/8acb8a3c-6ad0-4255-a59e-867c8c6db7af">

## Data Model
### Data Modeling
The data model consists of one fact table and several dimension tables. The fact table is the core of the model, containing quantitative data for analysis, while the dimension tables provide descriptive context. The relationships between the tables are visualized using an Entity-Relationship Diagram (ERD), which forms a star schema for efficient data organization.

### Tables
- Fact Table: SalesOrders
- Dimension Tables: Products, Customers, Calendar, Target_Gross_Margin(KPI), Target_Sales(KPI)

### Key Features
- Primary Keys (PK): Defined for each table to uniquely identify records.
- Foreign Keys (FK): Established from the fact table to dimension tables to define many-to-one relationships.
- Star Schema: Ensures efficient querying and reporting by centralizing the fact table and connecting it to surrounding dimension tables.

## Data Cleaning & Data Transformation(SQL)

To prepare the data for analysis, several tables were extracted and transformed using SQL. This process involved cleaning the data to ensure accuracy and consistency, as well as transforming it to meet the business requirements defined by the Sales Manager.

## Dashboard
[Try it out!](https://public.tableau.com/views/Salesdashboard_17168646680020/SalesOverview?:language=zh-TW&:sid=&:display_count=n&:origin=viz_share_link)
The finished Sales Performance Dashboard has three pages 
- Sales overview

The Sales Overview page offers a high-level summary of key sales metrics. It provides a snapshot of the overall sales performance, allowing stakeholders to quickly assess the health of the business and identify trends.

  <img width="1010" alt="Screenshot 2024-05-28 at 12 06 03 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/d98bce5d-fa4f-40c4-a58b-54fa218bc684">

- Products Detail

The Products Detail page focuses on the performance of individual products. It provides detailed insights into which products are driving revenue and how product sales are trending over time.

  <img width="1010" alt="Screenshot 2024-05-28 at 12 06 14 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/00a3fad1-56b0-46fe-81d9-b9f27a635821">

- Customers Detail

The Customers Detail page delves into customer-specific data, providing insights into customer purchasing behavior and preferences. This page helps to understand customer dynamics and tailor strategies to enhance customer satisfaction and retention.

  <img width="1009" alt="Screenshot 2024-05-28 at 12 06 24 AM" src="https://github.com/clairetsao/Automated_Sales_KPI_Dashboard/assets/145289997/d951806f-7459-4248-a1a7-dc81ee24e691">

