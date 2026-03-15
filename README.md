# Case Study: E-Commerce Sales Performance Analysis

## Business Problem

E-commerce businesses generate large volumes of transaction data, but without structured analysis it can be difficult to identify key revenue drivers and sales patterns.

This project analyzes **100,000 e-commerce transactions** to answer several important business questions:

* Which markets generate the highest revenue?
* Which product categories drive business performance?
* Are there seasonal trends in sales?
* Which products contribute most to revenue?
* How do different order sizes affect overall sales?

The goal of this analysis is to build an **interactive analytics dashboard** that helps stakeholders quickly understand sales performance and explore trends across multiple dimensions.

---

## Data Overview

The dataset contains **100,000 transaction records** representing sales activity across multiple countries and product categories.

| Column     | Description                      |
| ---------- | -------------------------------- |
| Order_ID   | Unique identifier for each order |
| Order_Date | Date of the transaction          |
| Country    | Customer country                 |
| Category   | Product category                 |
| Product    | Product name                     |
| Quantity   | Number of items purchased        |
| Unit_Price | Price per item                   |
| Revenue    | Total transaction value          |

The dataset provides sufficient scale and diversity to simulate real-world e-commerce analysis.

---

## Data Preparation

To prepare the dataset for analysis, several transformations were performed:

### Feature Engineering

Additional columns were created to improve analytical flexibility:

| Feature         | Purpose                               |
| --------------- | ------------------------------------- |
| Year            | Enables yearly analysis               |
| Month_No        | Maintains chronological month sorting |
| Month           | Used for trend visualization          |
| Revenue_Segment | Categorizes orders by revenue value   |
| Order_Size      | Categorizes transactions by quantity  |

These engineered features enable segmentation analysis and improved time-series visualization.

---

## Analytical Approach

The analysis was conducted using **Microsoft Excel** with Pivot Tables and Pivot Charts.

Key analytical techniques included:

* Data aggregation using Pivot Tables
* Time-series analysis of revenue trends
* Product-level performance analysis
* Market segmentation by country
* Order value segmentation

Interactive **slicers** were added to enable dynamic filtering by:

* Country
* Category
* Month

This allows users to explore the data from multiple perspectives.

---

## Dashboard Design

The final dashboard presents key business metrics and insights in an interactive format.

### Key Performance Indicators

The dashboard highlights four core metrics:

* Total Revenue
* Total Orders
* Units Sold
* Average Order Value

These KPIs provide a high-level overview of business performance.

---

### Interactive Visualizations

The dashboard includes the following visualizations:

| Visualization         | Purpose                             |
| --------------------- | ----------------------------------- |
| Revenue by Country    | Identifies top-performing markets   |
| Revenue by Category   | Shows product category contribution |
| Monthly Revenue Trend | Reveals seasonal sales patterns     |
| Top 10 Products       | Highlights highest revenue products |
| Revenue by Segment    | Analyzes order value distribution   |

All visualizations update dynamically when filters are applied.

---

## Key Insights

Several insights emerged from the analysis:

### Product Demand Concentration

A small number of products contribute a significant share of total revenue, demonstrating the importance of maintaining inventory and marketing focus on high-performing products.

---

### Category-Level Revenue Drivers

Certain product categories generate significantly more revenue than others, suggesting that strategic investment in these segments could improve overall business performance.

---

### Seasonal Revenue Patterns

Monthly revenue trends reveal fluctuations in sales performance, indicating potential seasonal demand cycles or promotional effects.

---

### Market Performance Differences

Revenue distribution across countries shows that some markets outperform others, highlighting opportunities for targeted marketing and expansion strategies.

---

### Order Value Segmentation

Revenue segmentation shows how different order sizes contribute to total sales, providing insights into customer purchasing behavior and opportunities to increase average order value.

---

## Business Value

This dashboard enables decision-makers to:

* Identify high-performing products and categories
* Understand regional revenue performance
* Detect seasonal sales patterns
* Explore customer purchasing behavior

By consolidating these insights into a single interactive dashboard, stakeholders can quickly analyze business performance and make data-driven decisions.

---

## Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Slicers
* Excel Dashboard Design
