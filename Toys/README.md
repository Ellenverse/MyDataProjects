# Retail Sales Performance Overview /Educational Project

This project is designed as training material to practice building Key Performance Indicator (KPI) dashboards. It demonstrates how to quickly aggregate and visualize the core financial results and sales structure of a retail business.

## Data Sources

This project uses a **complex data model** built from multiple interconnected tables. All source files are located in the **/data** folder of this repository:

* **Transactions (sales.xlsx):** The main fact table containing details of all orders and sales (used to calculate Total Orders, Revenue, and Profit).
    * *File Link:* [sales.xlsx](../data/sales.xlsx)
* **Products (products.xlsx):** The product dimension table used for order categorization (Orders by Product Category: Toys, Art & Crafts, etc.).
    * *File Link:* [products.xlsx](../data/products.xlsx)
* **Stores (stores.xlsx):** The store dimension table necessary for filtering by Store Location (Airport, Commercial, etc.).
    * *File Link:* [stores.xlsx](../data/stores.xlsx)
* **Calendar (calendar.xlsx & calendar.csv):** The date dimension table necessary for accurate time-series analysis (Revenue by Month).
    * *File Links:* [calendar.xlsx](../data/calendar.xlsx), [calendar.csv](../data/calendar.csv)
* **Inventory (inventory.xlsx):** Data related to stock levels or inventory tracking (used for supply management insights).
    * *File Link:* [inventory.xlsx](../data/inventory.xlsx)
* **Data Dictionary (data_dictionary.xlsx):** A descriptive file outlining all fields and metrics within the dataset.
    * *File Link:* [data_dictionary.xlsx](../data/data_dictionary.xlsx)

---

## Learning Objectives

The main objective is to practice creating dashboards focused on essential financial metrics:
* **KPI Cards:** Building dynamic large-number visuals to display **Total** financial performance.
* **Data Modeling:** Connecting data tables to calculate accurate **Revenue** and **Profit** figures.
* **Slicers:** Utilizing filters based on **Store Location** (Airport, Commercial, Downtown, Residential) to enable drill-down analysis.

---

## Dashboard Overview and Key Metrics

### 1. Overall Financial Performance (KPIs)

| Metric | Value | Insight |
| :--- | :--- | :--- |
| **Total Orders** | **41,830** | The total volume of transactions over the period. |
| **Revenue** | **$658,194** | The core financial measure of the business. |
| **Profit** | **$180,445** | An indicator of business efficiency and profitability. |

* **Skill Demonstrated:** Creating KPI cards and using visual background elements to enhance the impact of key metrics.

### 2. Order Structure (Orders by Product Category)

* **Leading Categories:** **Toys** and **Art & Crafts** generate the highest volume of orders (over 200,000 each).
* **Actionable Insight:** The low performance of **Electronics** and **Sports & Outdoors** may warrant a specific sales initiative or inventory review.
* **Skill Demonstrated:** Ranking data using horizontal bar charts to quickly identify top performers.

### 3. Revenue Dynamics (Revenue by Month)

* **Observation:** Revenue shows significant fluctuations, with a **pronounced peak** at the beginning of 2023, followed by a decline. This suggests strong seasonality or a major one-time event.
* **Skill Demonstrated:** Analyzing seasonality and trends using a line chart to visualize performance over time.

---

## Technical Details

| Aspect | Details |
| :--- | :--- |
| **Tool Used** | Power BI Desktop / Excel |
| **Key Technologies** | Data aggregation, measure creation, time-series analysis |
| **Data Type** | Aggregated retail sales performance data |
| **Filtering Capabilities** | By Store Type (Airport, Commercial, Downtown, Residential) |

## Project Visualization

![Screenshot of the Retail Sales Overview Dashboard](../images/retail_sales_overview.png)