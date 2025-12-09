# Power BI Project – AdventureWorks Sales Dashboard

## Project Overview
This project showcases an end-to-end Business Intelligence (BI) workflow using **Power BI Desktop**.  
The goal is to transform raw business data into meaningful, interactive dashboards that support **data-driven decision-making**.

This project simulates real-world tasks such as:
- Connecting and transforming datasets using **Power Query**
- Building a **relational data model** with fact and dimension tables
- Creating **measures and calculations** using **DAX**
- Designing **interactive dashboards** with KPIs, slicers, and custom visuals

The project is based on the *AdventureWorks* dataset — a fictional company specializing in manufacturing and selling bicycles and related products.

---

## Key Learning Objectives
- Apply the complete **data analytics lifecycle**: data preparation → modeling → visualization.
- Build efficient **Power Query transformations** for data cleaning and integration.
- Develop **DAX measures** for advanced business metrics (e.g., revenue growth, regional trends, customer segmentation).
- Design professional **report pages** for management and operational insights.
- Implement **data storytelling principles** for clarity and business relevance.

---

## Dashboard Features
- **Executive Overview** – KPIs for total sales, profit margin, and year-over-year performance  
- **Regional Insights** – Comparative analysis by country or sales territory  
- **Product Analysis** – Identify top-performing categories and individual products  
- **Customer Analysis** – Segment customers by value and purchasing behavior  
- **Time Intelligence** – Monthly and quarterly performance trends  

---

## Data Model
The project follows a **Star Schema** with clear separation between fact and dimension tables:

- **Sales Data** – Transaction-level sales data (fact)
- **Returns Data** – Data concerning order returns (fact) 
- **Customer Lookup** – Customer information (dim)
- **Product Lookup** – Product catalog (dim)
- **Product Category Lookup** - Product categories (dim)
- **Product Subcategory Lookup** - Product subcategories (dim)
- **Calendar Lookup** – Calendar table for time intelligence (dim) 
- **Territory Lookup** – Regional and country hierarchy (dim) 

---

## Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data modeling, DAX, visualization |
| **Power Query** | Data extraction and transformation |
| **SQL** | Initial data exploration |

---

