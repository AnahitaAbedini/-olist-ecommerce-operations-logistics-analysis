# E-Commerce Operations & Logistics Performance Analysis

A management-focused Python analysis of the Brazilian Olist e-commerce dataset, connecting sales performance, freight efficiency, delivery reliability, and customer satisfaction.

## Project Overview

This project analyzes e-commerce operations from a business and logistics perspective.

**Sales exposure → Logistics burden → Delivery performance → Customer impact → Management priority**

## Objectives

- Measure sales, order volume, and average order value.
- Evaluate freight cost relative to sales.
- Separate gross activity from realized delivered sales.
- Identify high-priority product categories.
- Measure late-delivery performance.
- Compare customer reviews for late and on-time deliveries.
- Translate results into operational recommendations.

## Dataset

Brazilian E-Commerce Public Dataset by Olist.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analytical Workflow

1. Load and inspect the datasets.
2. Standardize order lifecycle dates.
3. Merge orders, products, sellers, and categories.
4. Create sales and logistics KPIs.
5. Analyze product-category performance.
6. Measure delivery performance.
7. Connect delivery performance with customer reviews.

## Key Findings

| Metric | Result |
|---|---:|
| Realized sales | R$13.22M |
| Delivered orders | 96,478 |
| Average order value | R$137.04 |
| Freight / sales ratio | 16.63% |
| Sales realization rate | 97.28% |
| Late-delivery rate | 8.11% |
| Late-delivery review score | 2.57 / 5 |
| On-time/early review score | 4.29 / 5 |
| Customer satisfaction gap | 1.73 points |

High-priority categories contribute around **30.76% of realized sales**
but account for **40.85% of realized freight**.

## Operational Priorities

Focus logistics improvements on categories such as:

- Bed & bath table
- Furniture decor
- Housewares
- Garden tools
- Telephony
- Office furniture
- Electronics

Potential improvements include packaging optimization, shipment
consolidation, carrier selection, seller-level logistics improvements,
delivery exception management, and proactive customer communication.

## Management Takeaway

The project supports a targeted logistics optimization strategy rather
than blanket cost reduction, prioritizing areas where commercial
importance, freight burden, delivery risk, and customer impact overlap.
