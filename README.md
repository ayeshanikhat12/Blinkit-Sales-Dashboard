# Blinkit Sales Dashboard

**A Power BI Dashboard Project**

## 1. Project Overview

The **Blinkit Sales Dashboard** is a data visualization project developed using Microsoft Power BI to present key sales and order metrics through an interactive, business-oriented dashboard.

The project focuses on summarizing sales performance, order volume, and average order value. It demonstrates the use of data preparation, KPI reporting, and visual storytelling to convert raw data into an accessible business summary.

> **Project note:** This is an independent analytical project using a sample dataset. It is not an official Blinkit report.

## 2. Business Objective

The objective is to build a clear and concise dashboard that helps stakeholders review key sales indicators at a glance.

The project aims to:

- Summarize total sales and order volume.
- Calculate the average order value.
- Present sales distribution across item-type and city categories.
- Demonstrate how Power BI can support business reporting and exploratory analysis.
- Identify data-quality issues that should be addressed before making operational decisions.

## 3. Tools and Technologies

- **Microsoft Power BI Desktop** — dashboard development and data visualization
- **Python (Pandas)** — data preparation and cleaning
- **Google Colab** — Python-based analysis environment
- **SQL (SQLite)** — querying and exploring structured data
- **CSV** — source data format

## 4. Dataset Overview

The dataset contains **25 records** and the following fields:

| Column | Description |
|---|---|
| `order_id` | Order identifier |
| `item_type` | Item-type category |
| `outlet_id` | Outlet identifier |
| `order_value` | Recorded order value |
| `delivery_minutes` | Recorded delivery-time value |
| `city` | City category |
| `rating` | Recorded rating value |
| `order_date` | Order date |

The field meanings are based on the available column names. The units, category labels, and business definitions require confirmation from the original data source.

## 5. Dashboard Features

The dashboard presents the following KPIs and visualizations:

### Key Performance Indicators

- **Total Sales:** 2,400 recorded value units
- **Total Orders:** 25
- **Average Order Value:** 96 recorded value units per order

### Visualizations

- **Sales by Item Type:** Displays the recorded sales distribution across item-type categories.
- **Sales by City:** Displays the recorded sales distribution across city categories.
- **KPI Cards:** Provide a quick overview of the main sales indicators.

## 6. Key Observations

Based on the current sample dataset:

- The dataset contains 25 order records.
- Total recorded order value is 2,400 units.
- Average recorded order value is 96 units per order.
- The dashboard provides a consolidated view of the available sales metrics.

These are descriptive results from the supplied dataset. They should not be interpreted as verified Blinkit business performance or as evidence of trends across the wider business.

## 7. Data Quality and Limitations

The current dataset has important limitations:

- **Small sample size:** 25 records are insufficient for reliable business-wide conclusions.
- **Category labels:** Values such as `item_type_75` and `city_40` appear coded and require meaningful labels.
- **Delivery-time values:** The recorded values are unusually large for minute-based delivery times and require validation.
- **Rating values:** Some recorded values exceed common customer-rating scales and require clarification.
- **Currency and units:** The currency for `order_value` has not been confirmed.
- **Category coverage:** Item-type and city categories appear unique across the available records, limiting meaningful category comparisons.

For these reasons, the dashboard should currently be treated as an exploratory reporting project.

## 8. Business Value

This project demonstrates a practical reporting workflow: preparing structured data, calculating core metrics, and presenting results in a visual format.

With validated data and broader coverage, a dashboard of this type could help stakeholders monitor sales, compare categories, and identify areas for further investigation.

## 9. Conclusion

The **Blinkit Sales Dashboard** demonstrates foundational skills in data preparation, SQL-based data exploration, KPI reporting, and Power BI visualization.

The current version establishes a clear reporting structure while documenting the data limitations that must be resolved before drawing stronger business conclusions.

---

**Project Type:** Data Analytics / Business Intelligence  
**Status:** Initial dashboard version  
**Primary Tool:** Microsoft Power BI Desktop

## Dashboard Preview

![Blinkit Sales Dashboard](https://github.com/ayeshanikhat12/Blinkit-Sales-Dashboard/blob/ef9dd23dd23cf49db4dfd808bea5ae653e65ac52/Blinkit_Sale.png)


