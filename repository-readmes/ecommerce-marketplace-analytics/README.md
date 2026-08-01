<p align="center">
  <img src="./assets/banner.svg" alt="Ecommerce Marketplace Analytics" width="100%" />
</p>

# Ecommerce Marketplace Analytics

<p>
  <img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=58A6FF" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-0D1117?style=flat-square&logo=mysql&logoColor=58A6FF" alt="SQL" />
  <img src="https://img.shields.io/badge/Pandas-0D1117?style=flat-square&logo=pandas&logoColor=F0F6FC" alt="Pandas" />
  <img src="https://img.shields.io/badge/Power%20BI-0D1117?style=flat-square&logo=powerbi&logoColor=FF9900" alt="Power BI" />
</p>

## Overview

Ecommerce Marketplace Analytics is an end-to-end business intelligence project for understanding marketplace performance across orders, revenue, product categories, customer behavior, and operational trends.

## Business Problem

Marketplace teams need visibility into what is selling, where growth is coming from, which categories need attention, and how customer demand changes over time. Raw order tables are useful, but decision makers need cleaned metrics, clear trends, and focused dashboard views.

## Objectives

| Objective | Outcome |
| --- | --- |
| Analyze marketplace revenue | Track sales, order volume, and revenue movement. |
| Understand product performance | Compare categories, products, and contribution to revenue. |
| Study customer behavior | Identify purchase patterns and repeat activity. |
| Build a BI-ready model | Prepare clean tables for dashboarding and stakeholder review. |

## Dataset

The project is structured around ecommerce order data with order ids, customer ids, order dates, product categories, prices, quantities, payment mode, delivery status, region, and revenue fields. The dataset can be extended with customer and product dimension tables for richer analysis.

## Architecture

```text
Order Data
  -> Cleaning and Type Normalization
  -> Revenue and KPI Calculation
  -> Customer and Product Segmentation
  -> SQL Analysis Layer
  -> Power BI Dashboard
  -> Business Recommendations
```

## Folder Structure

```text
.
|-- data/
|   |-- raw/
|   `-- processed/
|-- notebooks/
|   `-- marketplace_analysis.ipynb
|-- sql/
|   |-- revenue_analysis.sql
|   `-- customer_segments.sql
|-- reports/
|   |-- figures/
|   `-- marketplace_dashboard.pbix
|-- assets/
|   `-- banner.svg
|-- README.md
`-- requirements.txt
```

## Tech Stack

| Layer | Tools |
| --- | --- |
| Data preparation | Python, Pandas, NumPy |
| Analysis | SQL, MySQL |
| Visualization | Power BI, Matplotlib, Seaborn |
| Version control | Git, GitHub |

## Installation

```bash
git clone https://github.com/arpittyagi-at/ecommerce-marketplace-analytics.git
cd ecommerce-marketplace-analytics
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Results

The completed analysis delivers revenue trends, product-category performance, customer purchase patterns, and dashboard-ready KPIs. The final output identifies high-performing categories, sales seasonality, customer concentration, and operational areas that affect marketplace performance.

## Screenshots

| View | File |
| --- | --- |
| Executive dashboard | `reports/figures/executive_dashboard.png` |
| Category analysis | `reports/figures/category_performance.png` |
| Customer behavior | `reports/figures/customer_behavior.png` |

## Next Improvements

| Improvement | Business Value |
| --- | --- |
| Add cohort analysis | Track repeat purchases and retention. |
| Add regional performance views | Improve market-level decision making. |
| Add forecasting | Estimate future demand and inventory needs. |
| Automate dashboard refresh | Keep KPIs current for stakeholders. |

## License

This project is released under the MIT License.
