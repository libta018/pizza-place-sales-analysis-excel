::: {align="center"}
# 🍕 Pizza Place Sales Analysis

### Turning 2015 pizza sales data into actionable business insights with Microsoft Excel

**An interactive Excel dashboard and business analysis report**

[![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Year](https://img.shields.io/badge/Data-2015-orange?style=for-the-badge)](#-dataset)
[![Focus](https://img.shields.io/badge/Focus-Sales%20Analytics-blue?style=for-the-badge)](#-business-objectives)
:::

------------------------------------------------------------------------

## 📌 Project Overview

This project explores **one year of pizza sales data (January--December
2015)** to understand sales performance, customer ordering patterns,
product preferences, and peak business hours.

Using **Microsoft Excel**, I cleaned and combined the data, created
Pivot Tables and interactive visualizations, and built two dashboards to
turn raw sales records into clear business insights.

The analysis is designed to help restaurant management understand what
sells best, when demand is highest, which products need attention, and
where promotional opportunities may exist.

## 📊 Dashboard Preview

### 1. Sales Overview

![Pizza Place Sales Dashboard 1](Dashboard%201%20%E2%80%93%20Sales%20Overview.png)

This dashboard provides a high-level view of business performance,
including revenue, order value, pizza quantity, ordering trends,
category contribution, and pizza-size preferences.

### 2. Product Performance

![Pizza Place Sales Dashboard 2](Dashboard%202%20%E2%80%93%20Product%20Performance.png)

This dashboard compares the top- and bottom-performing pizzas across
revenue, quantity sold, and number of orders, helping identify products
that perform well and those that may need review.


## 🎯 Business Objectives

-   Understand overall sales performance and key business metrics.
-   Identify peak ordering hours and daily customer trends.
-   Analyze sales contribution by pizza category and size.
-   Find the best- and worst-performing pizzas.
-   Translate the findings into practical recommendations to support
    revenue growth.

## 🗂️ Dataset

The analysis covers pizza sales transactions from **January 1 to
December 31, 2015**.

The project uses four related data tables:

  -----------------------------------------------------------------------
  Table                               Description
  ----------------------------------- -----------------------------------
  `orders`                            Order-level information, including
                                      order date and time

  `order_details`                     Pizza items and quantities
                                      associated with each order

  `pizzas`                            Pizza size, price, and product
                                      details

  `pizza_types`                       Pizza names, categories, and
                                      ingredients
  -----------------------------------------------------------------------

*Dataset source/link: add the original dataset URL here.*

## 🛠️ Tools & Techniques

  -----------------------------------------------------------------------
  Tool / Feature                      How it was used
  ----------------------------------- -----------------------------------
  Microsoft Excel                     Data preparation, analysis, and
                                      dashboard development

  Pivot Tables                        Summarizing sales by date, time,
                                      category, size, and product

  VLOOKUP                             Combining information from related
                                      tables

  Filters & Timeline                  Interactive date-based exploration

  Charts & KPI Cards                  Communicating business performance
                                      visually

  Data Cleaning                       Checking duplicates, missing
                                      values, and data formats
  -----------------------------------------------------------------------

## 🔄 Project Workflow

1.  **Data understanding** --- Reviewed the four tables and identified
    the fields needed for sales analysis.
2.  **Data cleaning** --- Checked for duplicate records, missing values,
    and inconsistent date or number formats.
3.  **Data preparation** --- Combined related information using VLOOKUP
    to create a useful analysis dataset.
4.  **Exploratory analysis** --- Examined revenue, order value, pizza
    quantity, order timing, category mix, size mix, and product
    performance.
5.  **Dashboard development** --- Built two interactive Excel dashboards
    using Pivot Tables, charts, KPI cards, filters, and a timeline.
6.  **Insight generation** --- Interpreted the results and prepared
    recommendations for menu planning, promotions, and operations.

## 📈 Key Performance Indicators

  KPI                                        Result
  ------------------------------ ------------------
  **Total Revenue**                **\$817,860.05**
  **Total Pizzas Sold**                  **49,574**
  **Total Orders**                       **21,350**
  **Average Order Value**               **\$38.31**
  **Average Pizzas per Order**             **2.32**

## 🔍 Key Insights

### 1. Ordering trends

-   The busiest lunch period is **12:00 PM--1:00 PM**.
-   Evening demand is strongest between **4:00 PM and 7:00 PM**.
-   The dashboard indicates an average of approximately **60 customers
    per day**.

### 2. Pizza category performance

  Category     Share of Sales   Pizzas Sold
  ---------- ---------------- -------------
  Classic              26.91%        14,888
  Supreme              25.46%        11,987
  Chicken              23.96%        11,050
  Veggie               23.68%        11,649

**Finding:** Classic is the leading category by both sales share and
quantity sold.

### 3. Pizza size preferences

  Size           Share of Sales
  ------------ ----------------
  Large (L)              45.89%
  Medium (M)             30.49%
  Small (S)              21.77%
  XL                      1.72%
  XXL                     0.12%

**Finding:** Large pizzas account for the biggest share of sales, while
XL and XXL contribute relatively little.

### 4. Top 5 pizzas by revenue

    Rank Pizza                             Revenue
  ------ ------------------------------ ----------
       1 The Thai Chicken Pizza           \$43,332
       2 The Barbecue Chicken Pizza       \$41,683
       3 The California Chicken Pizza     \$40,167
       4 The Classic Deluxe Pizza         \$37,632
       5 The Spicy Italian Pizza          \$34,164

### 5. Lowest-performing pizza

**The Brie Carre Pizza** is the weakest performer in the analysis:

-   Lowest revenue: **\$11,352**
-   Lowest quantity sold: **490 pizzas**

This product may need a closer review of its pricing, positioning,
customer feedback, and menu relevance before any decision is made.

### 6. Seasonality

The analysis indicates stronger sales during **Spring and Summer**, with
**Fall** being the weakest season.

## 💡 Business Recommendations

  -----------------------------------------------------------------------
  Area                    Recommendation          Expected business
                                                  benefit
  ----------------------- ----------------------- -----------------------
  Staffing                Schedule sufficient     Better service during
                          staff during 12 PM--1   busy periods
                          PM and 4 PM--7 PM       

  Inventory               Plan ingredients around Fewer stock-outs and
                          peak hours and popular  less waste
                          pizzas                  

  Menu optimization       Review consistently     Better use of menu
                          low-performing products space and resources
                          such as The Brie Carre  
                          Pizza                   

  Promotions              Test targeted offers    Potential improvement
                          during slower periods,  in demand
                          particularly Fall       

  Combos                  Experiment with         Encourage higher order
                          pizza-and-drink or      value
                          multi-pizza deals       

  Customer feedback       Collect reviews and     Better menu and service
                          survey customers about  decisions
                          less popular products   
  -----------------------------------------------------------------------

> These are recommendations based on the observed sales patterns. Their
> actual impact should be measured through follow-up analysis or
> controlled promotions.

## 📁 Repository Structure

``` text
pizza-place-sales-analysis-excel/
│
├── images/
│   ├── dashboard-1.png
│   └── dashboard-2.png
│
├── Pizza_Place_Sales_Dashboard.xlsx
├── PIZZA_PLACE_SALES_ANALYSIS_REPORT.pdf
└── README.md
```

## 🚀 How to Explore the Project

1.  Clone or download this repository.
2.  Open `Pizza_Place_Sales_Dashboard.xlsx` in Microsoft Excel.
3.  Navigate to the dashboard sheets.
4.  Use the available filters and date timeline to explore the sales
    data.
5.  Refer to `PIZZA_PLACE_SALES_ANALYSIS_REPORT.pdf` for the written
    analysis and recommendations.

## 📌 Project Outcome

This project demonstrates how Excel can be used to transform raw
transactional data into an interactive sales analysis solution. It
combines data cleaning, data preparation, exploratory analysis, KPI
reporting, visualization, and business recommendations in one end-to-end
project.

## 👨‍💻 Author

**Mohammed Talib**\
B.Tech --- Computer Science & Engineering (2025)

-   **LinkedIn:**
    [mohammed-talib-analytics-ds](https://www.linkedin.com/in/mohammed-talib-analytics-ds)
-   **GitHub:** [libta018](https://github.com/libta018)
-   **Email:** <mohammedtalib306@gmail.com>

------------------------------------------------------------------------

::: {align="center"}
**If you found this project useful, consider giving the repository a
⭐**

*Built with curiosity, Excel, and data-driven thinking.*
:::
