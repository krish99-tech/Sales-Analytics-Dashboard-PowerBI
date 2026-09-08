# Sales Analytics Dashboard — Power BI

An end-to-end business intelligence project built in Power BI Desktop, analyzing retail sales data across customers, products, and regions. This project demonstrates the full analytics workflow: data modelling, DAX measure development, and multi-page interactive dashboard design.

---

## Business Questions This Dashboard Answers

- Which regions and states generate the most revenue?
- Which product categories and sub-categories drive the highest sales?
- How does sales performance trend over time?
- Who are the highest-value customers and what is the average spend per customer?
- How does ship mode affect order volume and sales distribution?

---

## Dataset

**Source:** Sample US retail superstore transaction data  
**Scope:** Multi-year sales records across product categories, customer segments, and US states  
**Tables:** 5 structured tables built from raw source data via Power Query

---

## Data Modelling — Star Schema

One of the core decisions in this project was structuring the data into a proper star schema rather than working from a flat file. This involved splitting the raw data into a central Fact table and four Dimension tables, defining one-to-many relationships, and ensuring all measures aggregated correctly across every dimension.
