<img width="1304" height="739" alt="image" src="https://github.com/user-attachments/assets/9f3bd612-db2d-4b0d-85d3-b44098114613" />
<img width="1297" height="731" alt="image" src="https://github.com/user-attachments/assets/41618f41-4f9b-4a58-afcb-029bb3ef5f66" />
<img width="925" height="523" alt="image" src="https://github.com/user-attachments/assets/69e3be6e-41db-4d86-b338-6e5c4d6734c3" />
<img width="1163" height="706" alt="image" src="https://github.com/user-attachments/assets/d626d2e8-cf8d-4018-84a1-197d88b2d559" />
# Product Performance Dashboard

An interactive **Power BI dashboard** designed to analyze product sales performance and provide clear insights into orders, quantity, sales, freight, and tax.

## Data Modeling

The dataset was transformed into a **Star Schema** consisting of:

* **Fact Table:** Contains transactional sales data.
* **Product Dimension:** Contains product-related information.
* **Date Dimension:** Used for time-based analysis.
* **Status Dimension:** Provides order status details.
* **Territory Dimension:** Contains sales territory information.
* **Ship Mode Dimension:** Contains shipping method information.

The dimension tables are connected to the Fact table through appropriate relationships to create an efficient and structured data model.

## DAX Measures

Created the following measures to support the dashboard analysis:

* **Total Sales** – Calculates the total sales revenue.
* **Total Orders** – Calculates the total number of orders.
* **Total Quantity** – Calculates the total quantity of products sold.
* **Total Freight** – Calculates the total shipping cost.
* **Total Tax Amount** – Calculates the total tax amount.

## Dashboard Objectives

The dashboard provides insights into:

* Product sales performance.
* Best-performing products.
* Sales and quantity trends over time.
* Order performance.
* Freight and tax analysis.
* Performance across different territories, statuses, and shipping methods.

## Tools

**Power BI | Power Query | DAX | Data Modeling | Star Schema**



