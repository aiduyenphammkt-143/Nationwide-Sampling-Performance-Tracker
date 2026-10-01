# Sales Sampling Performance Dashboard
Built a scalable performance-tracking solution that helped ensure consistent execution of a nationwide product sampling campaign, supported weekly executive decision-making, and enabled proactive intervention for underperforming sales teams.

---

## Overview

This project was developed during the nationwide launch campaign of Nabati Strawberry Wafer at Nabati Vietnam.

As Project Lead, I was responsible for coordinating execution with Sales teams, monitoring campaign performance, and reporting progress to executive management.

To support these activities, I developed a Power BI dashboard that consolidated sampling execution and post-sampling sales performance into a single monitoring solution.

The dashboard helped answer two critical questions:

* Are sales teams executing the sampling program as planned?
* Is the new product gaining consumer acceptance after sampling activities?

---

## Business Challenge

The company launched a large-scale sampling program to introduce a new product to consumers.

- 100+ Distributor Sales Teams
- 13 Areas
- 3 Regions
- More than 1 year of nationwide implementation (separated into 2 phases)

Management needed a reliable way to:

* Monitor execution progress across the country
* Identify regions and distributors falling behind plan
* Measure the effectiveness of each sampling event
* Track whether sales performance improved after sampling
* Provide fact-based updates to leadership on a weekly basis

---

## ⚡ Solution

Developed a Power BI dashboard as the single source of truth for project monitoring and performance evaluation.

### Key Capabilities

* Track sampling execution progress against KPI
* Monitor event-level effectiveness:
    * Samples distributed
    * Orders generated
    * Conversion rate
    * Revenue
* Monitor performance from Region → Area → Distributor
* Drill down to Sales Supervisor level
* Flag underperforming teams for follow-up
* Support weekly executive reporting

### Business Impacts

* Ensured the sampling program was executed consistently across the organization and aligned with the product launch strategy
* Increased transparency and accountability from Region Manager to frontline Sales Supervisor
* Enabled sales leadership to use fact-based performance data to follow up and correct underperforming teams
* Provided early signals on consumer acceptance of the new product through post-sampling sales tracking

---

## Dashboard

<img src='./dashboard images/Executive Dashboard.png' width=1200>

---

## Project Workflow

```text
1. Marketing launches the sampling program and defines KPIs

        ↓

2. Sales teams load products into selected stores
   to ensure sufficient stock for sampling activities

        ↓

3. Sales Supervisors execute sampling events
   and submit execution reports

        ↓

4. Marketing consolidates sampling results
   and tracks post-sampling sales performance

        ↓

5. Dashboard monitors:

   - Execution progress
   - Sampling effectiveness
   - Sales uplift after sampling
   - Regional performance gaps

        ↓

6. Marketing follows up delayed teams,
   tracks post-performance, and reports results to executive leadership
```

---

## 🛠 Tools

- Power BI
- Power Query (M-language)
- Excel

---

## 📁 Repository Structure

```text
├── data/
│   ├── EcomSales.csv
│   └── Product.csv
│       └── Danh mục sản phẩm và thông tin phân loại
├── Nationwide Sampling Dashboard.pbix
│   └── Tiền xử lý dữ liệu, xây dựng mô hình Apriori và phân tích Association Rules
└── README.md
    └── Tổng quan dự án, kết quả phân tích và khuyến nghị kinh doanh
```
