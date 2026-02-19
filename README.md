Furniture BI Project
Overview

This project demonstrates business intelligence (BI) analysis on a furniture sales dataset. The goal was to explore sales, assembly requests, and delivery performance across brands, products, and payment methods, and create actionable dashboards using Power BI.

The dataset used is clean_furniture_data containing detailed sales, product, brand, and delivery information.

Project Objectives

Analyze total orders, revenue, and assembly requests across Brands and Product Categories

Monitor On-Time Delivery performance

Identify assembly service trends by Brand, Product Category, and Payment Method

Build interactive dashboards for stakeholders to track key KPIs

Dataset

Table name: clean_furniture_data

Columns include:

brand – Brand of the product

product_category / product_subcategory – Product grouping

assembly_service_requested – Whether assembly was requested (TRUE/FALSE)

delivery_status – Status of delivery (Delivered / Not Delivered)

delivery_window_days – Days taken to deliver

total_amount / product_price – Revenue metrics

payment_method – Customer payment type

Key Measures (DAX)
Overall Business Performance

Total Orders

Total Revenue

Assembly Requests

Assembly %

On-Time Deliveries

On-Time Delivery %

Brand Performance

Total Orders per Brand

Revenue per Brand

Assembly Requests per Brand

Assembly % per Brand

On-Time Deliveries per Brand

On-Time Delivery % per Brand

Product Performance

Total Orders per Product / Subcategory

Revenue per Product / Subcategory

On-Time Deliveries per Product

On-Time Delivery % per Product

Assembly Requests per Product

Assembly % per Product

Level Performance Revenue per Product / Subcategory

Assembly Analysis (Brand / Category)

Assembly Requests per Brand / Category

Assembly % per Brand / Category

Payment Method Analysis

Total Orders per Payment Method

Revenue per Payment Method

Assembly % per Payment Method

On-Time Delivery % per Payment Method

Dashboards & Visuals

Overall Business Performance

KPI Cards: Total Orders, Total Revenue, Assembly Requests

Donut / Stacked Column: Assembly %

Gauge: On-Time Delivery %

Brand Performance

Clustered Bar / Column: Total Orders & Revenue per Brand

Stacked Column / Donut: Assembly % per Brand

Column / Line Combo: On-Time Deliveries

Gauge: On-Time Delivery % per Brand

Product Performance

Matrix / Table: Total Orders & Revenue per Product / Subcategory

Clustered Bar: Top Products by Revenue or Orders

Stacked Column / Donut: Assembly % per Product / Subcategory

Column / Line Combo: On-Time Delivery %

Assembly Analysis

Clustered Bar: Assembly Requests by Brand / Product Category

Donut / Stacked Column: Assembly % by Brand / Product Category

Payment Method Analysis

Clustered Column / Bar: Total Orders & Revenue per Payment Method

Donut / Stacked Column: Assembly % per Payment Method

Gauge / Card: On-Time Delivery % per Payment Method

Tools & Technologies

Power BI: Dashboarding & data visualization

DAX: Measures for KPI calculations

Excel: Data cleaning, aggregation, and preliminary analysis

SQL (optional): For data extraction from relational sources

Python (optional): Data preprocessing and analytics

Skills Demonstrated

Data cleaning, validation, and transformation

KPI definition & measure creation with DAX

Interactive dashboard design in Power BI

Analytical thinking & trend identification

Reporting for business stakeholders
