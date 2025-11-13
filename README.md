# Northwind SQL Analytics Project

## Project Overview
This project analyzes the **Northwind Traders** dataset to uncover business insights such as top customers, supplier contributions, employee performance, and sales trends.  
The analysis was conducted using **PostgreSQL**, and the results were visualized with **Excel pivot tables and dashboards**.

---

##  Dataset
The project uses the **Northwind Traders** relational database, which contains customer orders, product sales, suppliers, shippers, and employee information.  

-  Source: [Northwind Database on Kaggle](https://www.kaggle.com/datasets/ahmedhamada0/northwind-database)  
-  Format: PostgreSQL (imported into pgAdmin / PostgreSQL for analysis)

---

##  Objectives
- Derive insights into revenue distribution, product performance, employee productivity and supplier contributions.  
- Identify growth/opportunity areas and inefficiencies (e.g., slow shipping, inactive customers/products).  
- Use SQL techniques (CTEs, Window Functions, Views).
- Build an **Excel Dashboard** for stakeholders to visulaize key insights.

---

## My Role & Workflow  
1. **Data preparation & import**: Imported the Northwind schema into PostgreSQL.  
2. **Query development**: Developed modular SQL queries to answer each business question, using techniques such as window functions for ranking,CTEs for readability and performance optimization.  
4. **Results extraction & visualization**: Exported query results into Excel, created meaningful pivot tables, slicers and charts, and arranged them into an interactive dashboard for stakeholder consumption.  
5. **Insight generation & recommendations**: Translated analytical findings into business-relevant recommendations (e.g., loyalty programmes for top customers, review shipping options, re-engage inactive customers).  

---

##  Business Questions Answered
1. Who are the top revenue-generating customers?  
2. Which suppliers contribute the most to product volume?  
3. Which employees process the most orders?  
4. How efficient are our shippers?  
5. What are the monthly sales trends for 1997?  
6. Which countries generate the highest average order value?  
7. Which products/customers had no orders?
- (and additional advanced queries such as returning customer behaviour, revenue percentile ranking, product quartiles)  

### Additional Queries
8. Which products were never ordered?  
9. Which customers had no orders in 1997?  
10. Revenue distribution by product category.  
11. Returning customers and time between orders.  
12. Products sold only once per order.  
13. Product revenue percentile rankings.  
14. Employees’ first order handled.  
15. Customer revenue quartiles.  
16. Yearly cumulative sales growth.  

---

## Tools & Technologies
- **PostgreSQL** – Data querying & analytics  
- **SQL** (CTEs, Window Functions, Views)** – Advanced analysis  
- **Excel** – Pivot tables, slicers, and dashboard visualization  

---

## Dashboard Preview
This dashboard visualizes the results of **7 SQL queries**, exported into Excel and transformed into pivot tables and charts. 
![Dashboard Preview](dashboard/Northwind_Sales_Dashboard.png) 

---

##  Key Insights & Implications
**Revenue & Customer Overview:**
- Total revenue of $1.27M was generated from 830 orders across 89 customers, with an average order value of $1,525.

**Employee Performance:**
- Margaret Peacock leads in both yearly sales and total orders, showing consistent top performance across all three years (1996–1998).
- Janet Leverling follows closely, highlighting strong revenue contribution.

**Supplier Performance:**
- Plutzer, Pavlova, and Specialty Biscuits supply the highest quantities (≈ 4,000 units each), making them essential trade partners.

**Shipping Efficiency:**
- Federal Shipping is the most efficient shipper with an average delivery time of 7.47 days, outperforming Speedy Express (8.57) and United Package (9.23).
- Prioritizing Federal Shipping could improve delivery reliability.

**Customer Insights:**
- QUICK-Stop, Ernst Handel, and Save-a-lot Markets are top revenue-generating customers — valuable targets for retention and upselling initiatives.

**Geographical Insights:**
- Austria, Ireland, and the USA show the highest average order values, suggesting these are high-potential markets for strategic investment.

**Sales Trend:**
-1997 sales show steady monthly performance with strong peaks in October and December, indicating seasonal demand patterns.

---

## How To Use

### 1. Clone the Repository
Run the following command to clone the project:

```bash
git clone https://github.com/linetrono/NORTHWIND-SALES-ANALYTICS-SQL-PROJECT.git
```

### 2. Setup
Import the Northwind database into your SQL environment (e.g., postgreSQL)

### 3. Explore Queries
Navigate to the Queries folder to explore specific analytical SQL queries.
Each .sql file contains a themed query, for example:

"Top Employees by Revenue"
"Regional Sales Distribution"

### 4. Visual Insights
Check the Images folder to view visualized results and insights corresponding to each query.

### 5. Dashboard
Open the dashboard file (e.g., Northwind_Sales_Dashboard.png) for an overview of key metrics and insights.

---

##  Documentation
Full project documentation available here:  
![NORTHWIND_SQL_ANALYTICS PDF](docs/Northwind_Sales_Analysis_Insight_Project.pdf)

---

## Contact
If you have any questions, feedback, or collaboration ideas, feel free to reach out:

- **Name:** Linet Mukami Rono  
- **Email:** [my email address](mukamihrono@gmail.com)  
- **LinkedIn:** [my linkedn profile](https://www.linkedin.com/in/linet-rono-b32130277/)  
- **GitHub:** [my GitHUb](https://github.com/linetrono)
