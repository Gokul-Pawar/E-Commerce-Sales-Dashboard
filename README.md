# E-commerce Sales Dashboard | Power BI

An interactive Power BI dashboard project for exploring e-commerce sales performance, profitability, customer behavior, product performance, payment preferences, and sales trends.

## Project Overview

The **E-commerce Sales Dashboard** is designed to help stakeholders understand sales performance and identify patterns that can support business decision-making. It uses order and sales-detail datasets and presents key metrics and business views in Power BI.

## Objectives

- Monitor revenue, quantity sold, profit, and average order value (AOV).
- Compare sales performance across states and cities.
- Identify high-performing product categories and sub-categories.
- Explore customer contributions to overall sales.
- Understand payment-mode preferences.
- Review monthly sales and profit trends.

## Tools & Files

- **Power BI Desktop** — dashboard/report development (`.pbix`).
- **CSV datasets** — source data.
- **DAX** — measures and calculations used in the report, where implemented.
- **PDF documentation** — project overview and described findings.
- **XMind files** — supporting mind maps/planning notes.

### Repository Structure

```text
ecommerce-sales-dashboard/
├── README.md
├── Sales Dashboard.pbix
├── Orders.csv
├── Details.csv
├── Ecommerce Sales Dashboard.pdf
├── Ecommerce Sales Dashboard.xmind
├── DAX Foundations(1).xmind
└── screenshots/
    └── dashboard-overview.png

## Dataset Overview

The project includes two CSV files:

### `Orders.csv`

Contains order-level information described in the project documentation, including:

- Order ID
- Order Date
- Customer Name
- State
- City

### `Details.csv`

Contains sales-detail information described in the project documentation, including:

- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode

## Dashboard KPIs

The project documentation describes the following key performance indicators (KPIs):

- **Total Revenue** — total amount generated from sales.
- **Total Quantity Sold** — number of items sold.
- **Overall Profit** — profit recorded across sales.
- **Average Order Value (AOV)** — average sales value per order, according to the measure used in the report.

## Business Questions

The dashboard is intended to help answer:

1. Which states contribute the most revenue?
2. Which product categories and sub-categories perform best?
3. How do sales change month over month?
4. Who are the top customers by sales?
5. Which payment modes are used most often?
6. During which months does profit increase or decrease?

## Findings Described in the Project Documentation

The supplied project PDF lists these observations:

- Printers are the most profitable sub-category.
- Maharashtra leads in sales by state.
- Cash on Delivery (COD) is the most preferred payment mode.
- Clothing is the highest-selling category, with a reported 63% share.
- Profit dips from May to August, suggesting a possible seasonal decline.
- Harjeet, Mohan, and Madam Mohan are listed among customers contributing substantially to sales.

## How to Open the Project

1. Download or clone this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open `Sales Dashboard.pbix`.
4. If Power BI prompts you to locate the source files, point it to `Orders.csv` and `Details.csv` in the downloaded project folder.
5. Use the report pages, filters, and slicers to explore the analysis.

## Screenshots

Add screenshots of the actual Power BI report to a `screenshots/` folder and embed them here. 

## Deployment / Viewing Online

The `.pbix` file can be stored in GitHub for download, but GitHub does not render it as an interactive Power BI report.

## Author

Gokul Katwale  
Aspiring Data Analyst | Power BI | Excel | SQL


## License
MIT License
