### Olist E-Commerce SQL Analytics

This project performs exploratory data analysis (EDA) on the Brazilian E-Commerce dataset by Olist. It uses **Jupyter Notebooks + DuckDB** to query a structured database pre-modeled using a Medallion Architecture, providing direct insight generation without external BI tool dependencies.
[DB file](https://github.com/RahulShinde02/SQL-data-warehouse-Projects/releases/tag/v.1.0.0)

#### Core Analysis & SQL Techniques

* **Cohort Retention Analysis:** Maps lifecycle drop-off rates across purchase months using CTEs.
* **RFM Customer Segmentation:** Segments user purchasing habits by ranking scores with `NTILE`.
* **Pareto Analysis (80/20 Rule):** Isolates the core 16 product categories driving 80% of total revenue.
* **Logistics & Delivery Audits:** Pinpoints order transit delays against consumer review drops.
* **Materialized Summary Views:** Sets up `gold.mv_executive_summary` tracking long-term trends in volume, margins, active sellers, and rating metrics.
