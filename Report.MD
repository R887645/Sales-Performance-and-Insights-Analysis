# Sales Performance Dashboard to Identify Revenue Growth Opportunities for an e-commerce business

## Business Problem / Objective

The business wants to move from raw sales data to actionable insights.

Management needs clear visibility into:

- How sales and order volumes are trending over time  
- Which products and channels are driving revenue  
- Who the top customers are  
- Which regions and warehouses perform best or worst  
- Where revenue growth opportunities exist  

This project was designed to answer the core question:

**“How can the company optimize sales performance and focus on high-impact areas to drive sustainable revenue growth?”**

## Dataset Overview

- **Data Source:** Internal company sales records  
- **Time Period Covered:** 2020 – 2021  
- **Volume:** Over 16,000 sales transaction records  
- **Format:** CSV/Excel files

### Key Columns in the Dataset:

- Order Date  
- Product Description  
- Quantity Ordered  
- Revenue  
- Order Type  
- Customer Name  
- Region  
- Warehouse Code

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Main%20Dataset_sales.png?raw=true)

## Tools Used

- **Power Query** – Data cleaning and transformation  
- **Power BI** – Data modeling, dashboard design, visualization  
- **Microsoft PowerPoint** – Creating initial wireframes for dashboard layout and flow

## Data Cleaning & Preparation

- Removed duplicate records  
- Standardized date formats for proper time intelligence  
- Filled or handled missing values in revenue and quantity fields  
- Ensured consistent product and region naming  
- Converted numeric columns to correct data types
- Separate the fact table from Dimension tables (Order Fact table and Dimension Tables(Customer_DIM, Region, and Order_DIM))

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Sales_power%20Query.png?raw=true)


# Calendar Table Created for Time Intelligence
- Date
- Year
- Month
- MonthNum
- Quarter
- HalfMonth

# Data Modelling
- All the Tables are connected to the fact table to establish a strong relationship for easy analysis

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/SALES_Data%20modelling.png?raw=true)


### Calculated Measures Created:

- Total Revenue
- PM Revenue
- MOM Revenue
- Revenue Variance
- MOM Revenue Color
- Customer ranking by revenue  
- Average Order Value (AOV) 
- PM AOV
- MOM AOV
- AOV Variance
- MOM AOV Color
- Month-over-Month (MoM) Growth  
- Total Quantity 
- PM Quantity
- MOM Quantity
- Quantity Variance
- MOM quantity Color

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/calculated%20measure_sales.png?raw=true)

## Key Questions & Analysis

- How are total sales and order volumes trending over time?  
- Which products generate the highest revenue and order volume?  
- What is the average order value, and how does it vary across customers?  
- Are high-volume orders also high-revenue orders?  
- Which products are showing declining trends?  
- Which regions and warehouses contribute the most revenue?  
- Who are the top-performing customers?

## Key Insights

- **Overall sales increased by 9.8% in 2021**, driven by higher order volumes and improved Average Order Value.  
- **Chocolate Truffle emerged as the top-performing product**, generating over $1.6 million in revenue.  
- **Warehouse AXW291 contributed the highest revenue** across both years.  
- Strong positive correlation exists between **order quantity and revenue**, especially for wholesale and distributor customers.  
- The **West region consistently outperformed** other regions in total revenue.  
- The **Northeast region showed weaker performance**, indicating potential operational or market challenges.  
- The **top 5 customers generated more than 20% of total revenue**, showing significant customer concentration.

**[View the Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTIwNzZmYjAtY2FiOS00ZTQ4LTg0ZmEtYTZjZDNiMDY0YjcwIiwidCI6ImZjY2Y0MmRmLTE2ZDktNGU4Ny1hNmUwLWU0OTYyMjAxN2Y3NCJ9)**

## Recommendations

1. Try to focus marketing and promotions on high-performing products such as Chocolate Truffle and Nougat.  
2. Conduct a deeper investigation into the Northeast region to identify reasons for poor performance.  
3. Optimize inventory planning for top warehouses like AXW291 to prevent stockouts.  
4. Develop loyalty and retention programs for high-value customers.  
5. Monitor low-performing products for possible repositioning or discontinuation.  
6. Expand distribution strategies in high-growth regions such as the West.

## Dashboard / Visualization

Before creating the Power BI dashboard, I first designed **wireframes in PowerPoint** to plan the layout, page flow, and visual hierarchy. 
This ensured a clear structure and logical story before working with actual data.

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Slide9.PNG?raw=true)

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Slide10.PNG?raw=true)

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Slide11.PNG?raw=true)


The Power BI dashboard contains three main pages:

### 1. Sales & Order Trends Analysis
- Monthly and yearly revenue trends  
- Order volume patterns  
- Average Order Value analysis  
- Top products and top customers

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Sales_Overview_Page.png?raw=true)

### 2. Revenue Drivers & Performance Analysis
- Revenue contribution by warehouse  
- Product-level performance  
- Relationship between orders and revenue

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/sales_performance.png?raw=true)

### 3. Customer & Regional Insights
- Revenue by customer type  
- Regional performance comparison  
- Bottom customers analysis  
- Geographic revenue distribution

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/sales_Customer&regional.png?raw=true)

The dashboard is structured to tell a logical business story: **From trends → to drivers → to customer behavior**.

## How This Project Sharpened My Skills

This project significantly improved my Power BI skills, including:

- Advanced dashboard design and visualization  
- Creating dynamic calculated measures and DAX formulas  
- Implementing interactive filters, slicers, and bookmarks  
- Understanding the flow from raw data to actionable insights  
- Storytelling with data for business decision-making  
- Planning and designing dashboards effectively through wireframes in PowerPoint

![My Image Description](https://github.com/R887645/Sales-Performance-and-Insights-Analysis/blob/main/Slicer%20and%20reset%20bookmarks_sales.png?raw=true)

## Challenges Faced

During the project, I encountered a few challenges:

1. Setting up **slicer bookmarks** for dynamic filtering across multiple pages  
2. Configuring the **reset button** functionality, which required careful testing to ensure all slicers returned to the default state  

Overcoming these challenges helped me gain a deeper understanding of Power BI interactivity features.

## Conclusion

This project transformed raw transactional data into meaningful business insights. The analysis helped to:

- Identify key revenue drivers  
- Highlight regional performance gaps  
- Understand customer concentration  
- Support data-driven decision-making

The dashboard provides stakeholders with a powerful tool to monitor performance and plan strategic improvements.

## Limitations

- The dataset does not include marketing spend, customer demographics, or competitor data.  
- External factors such as seasonality, economic conditions, and supply chain disruptions were not captured.  

Including additional data sources could enable deeper and more predictive analysis.

I am Rofiah, Your Ecommerce, Sales, and Marketing Analyst
