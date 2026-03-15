# ecommerce-sales-excel-dashboard
# E-Commerce Sales Analytics Dashboard (Excel)

## Project Overview

This project analyzes **100,000 e-commerce transactions** to uncover sales trends, product performance, and customer purchasing patterns.

An **interactive Excel dashboard** was built using Pivot Tables, Pivot Charts, and Slicers to enable dynamic exploration of the data and support business decision-making.

The dashboard provides a clear view of revenue performance, product demand, and sales trends across countries and product categories.

---

## Dashboard Preview

![Dashboard Overview][Excel_Dashboard.png]

---

## Dataset

The dataset contains **100,000 transaction records** representing sales activity in an e-commerce business.

### Columns

| Column     | Description                    |
| ---------- | ------------------------------ |
| Order_ID   | Unique order identifier        |
| Order_Date | Date when the order was placed |
| Country    | Customer country               |
| Category   | Product category               |
| Product    | Product name                   |
| Quantity   | Number of units sold           |
| Unit_Price | Price per unit                 |
| Revenue    | Total order value              |

---

## Data Preparation

The dataset was cleaned and transformed to support analysis and visualization.

### Key Transformations

* Created a **Clean_Data** table from the raw dataset
* Generated new analytical features:

| Feature         | Purpose                                       |
| --------------- | --------------------------------------------- |
| Year            | Enables yearly analysis                       |
| Month_No        | Maintains chronological sorting               |
| Month           | Used for monthly trend charts                 |
| Revenue_Segment | Categorizes order value (Low / Medium / High) |
| Order_Size      | Categorizes purchasing behavior               |

These transformations improved the ability to analyze trends and segment sales data.

---

## Analysis Performed

The project explores key business questions related to revenue performance, product demand, and sales trends. The analysis focuses on identifying revenue drivers, understanding purchasing behavior, and uncovering patterns that can inform business strategy.

### 1. Revenue by Country

This analysis examines the geographic distribution of sales to identify the most valuable markets.

**Key questions addressed:**

* Which countries generate the highest revenue?
* How concentrated are sales across markets?

**Purpose:**
Understanding regional performance helps businesses prioritize high-performing markets and identify opportunities for expansion or targeted marketing efforts.

---

### 2. Revenue by Product Category

Revenue was analyzed across product categories to determine which segments contribute the most to overall business performance.

**Key questions addressed:**

* Which product categories drive the majority of revenue?
* Are sales concentrated in a few categories or evenly distributed?

**Purpose:**
Category-level insights help businesses allocate resources effectively, optimize product portfolios, and identify underperforming segments.

---

### 3. Monthly Revenue Trend

A time-series analysis was performed to evaluate how revenue changes over time.

**Key questions addressed:**

* Are there seasonal patterns in sales?
* Which months show the strongest or weakest performance?

**Purpose:**
Trend analysis enables businesses to anticipate demand fluctuations, improve inventory planning, and design effective promotional campaigns.

---

### 4. Top 10 Products by Revenue

The analysis identifies the products that generate the highest revenue.

**Key questions addressed:**

* Which individual products contribute the most to total sales?
* Is revenue heavily driven by a small number of products?

**Purpose:**
Identifying top-performing products allows businesses to focus marketing, optimize pricing strategies, and maintain sufficient inventory for high-demand items.

---

### 5. Revenue Distribution by Order Segment

Orders were segmented based on revenue value to understand purchasing behavior across different transaction sizes.

**Segments:**

* Low Value Orders
* Medium Value Orders
* High Value Orders

**Key questions addressed:**

* Which order segments contribute most to total revenue?
* Do large orders dominate revenue or do smaller transactions accumulate significantly?

**Purpose:**
Segmenting orders helps businesses understand customer purchasing behavior and design strategies to increase average order value.

---

### Analytical Approach

The analysis was conducted using **Pivot Tables and Pivot Charts in Excel**, enabling rapid aggregation and interactive exploration of the dataset. The use of **slicers and dynamic filters** allows users to analyze revenue patterns across multiple dimensions such as country, category, and month.

---

## Dashboard Features

The Excel dashboard provides interactive exploration of the data.

### KPI Cards

The dashboard displays key performance indicators:

* Total Revenue
* Total Orders
* Units Sold
* Average Order Value

### Interactive Visualizations

* Revenue by Country
* Category Revenue Share
* Monthly Revenue Trend
* Top Products by Revenue
* Revenue Distribution by Segment

### Interactive Filters

Users can dynamically filter the dashboard using:

* Country
* Category
* Month

All charts update automatically when filters are applied.

### Data Label Toggle

A custom toggle control allows users to **show or hide chart data labels**, reducing visual clutter while allowing detailed inspection when needed.

---

## Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Slicers
* Excel Dashboard Design
* Data Visualization

---

## Key Insights

Some insights identified during the analysis:

* Certain product categories generate significantly higher revenue than others.
* Sales trends vary by month, indicating potential seasonal patterns.
* A small number of products contribute a large share of total revenue.
* Order size segmentation helps identify purchasing behavior across customers.

---

## Project Structure

```
ecommerce-sales-excel-dashboard
│
├── data
│   └── ecommerce_100k_dataset.xlsx
│
├── dashboard
│   └── ecommerce_sales_dashboard.xlsx
│
├── images
│   ├── dashboard_overview.png
│   ├── dashboard_filters.png
│   └── dashboard_products.png
│
└── README.md
```

---

## How to Use

1. Download the repository
2. Open the Excel dashboard file:

```
dashboard/ecommerce_sales_dashboard.xlsx
```

3. Use the slicers to filter the dashboard by:

* Country
* Category
* Month

4. Use the **data label toggle** to show or hide chart values.

---



---

## Author

**Yusuf M**

Aspiring Data Analyst focused on building practical data analytics projects using Excel, SQL, Python, and Power BI.

---

## License

This project is for **educational and portfolio purposes**.
