# Data Dictionary

## 1. Overview

The Hospitality Weekly Insight Hub uses Google BigQuery as its centralized data storage and query engine.

The demonstration architecture contains 11 tables distributed across two logical data domains.

This document describes the purpose of each table, its associated dashboard module, and the business metrics supported by it.

**Note:** Exact column names, data types, primary keys, and relationships will be added after inspecting the actual BigQuery table schemas.

## 2. Dataset: Executive Analytics

This dataset supports revenue reporting, workforce analytics, operational monitoring, and executive review.

| No. | Table Name | Dashboard Module | Business Purpose |
|---|---|---|---|
| 1 | `fnb_sale_demo` | Revenue | F&B revenue, order count, average order value, daily trends, payment modes and property comparisons |
| 2 | `fnb_targets_demo` | Revenue | Budget versus actual performance and target achievement |
| 3 | `fnb_item_sale_demo` | Revenue | Item-level sales and food category revenue |
| 4 | `sales_booking_demo` | Brand | Checkout counts, departure dates and guest review-rate calculations |
| 5 | `fo_upsell_demo` | Revenue | Front Office upselling revenue, categories, average upsell per room, performers and transaction logs |
| 6 | `fo_upsell_target_demo` | Revenue | Upselling budget targets by property |
| 7 | `training_attendance_demo` | People | Employees trained, training hours, sessions, categories and attendance rates |
| 8 | `hr_master_demo` | Property | Workforce headcount, new joiners, employee movement and attrition reasons |
| 9 | `guest_complaints_demo` | Property | Guest complaints, complaint categories, room records and resolution status |
| 10 | `points_to_discuss_demo` | Points to Discuss | Executive review items, departmental assignments and discussion status |

## 3. Dataset: Guest Experience

This dataset supports guest reputation and review analysis.

| No. | Table Name | Dashboard Module | Business Purpose |
|---|---|---|---|
| 11 | `Ratingsheet_demo` | Brand | Guest ratings, review platforms, sentiment trends and response rates |

## 4. Business Metrics Catalogue

### Revenue Analytics

| Metric | Description |
|---|---|
| Total Revenue | Total revenue generated during the selected reporting period |
| Order Count | Number of recorded orders |
| Average Order Value | Average revenue per order |
| Daily Revenue | Revenue movement across reporting dates |
| Payment Mode Breakdown | Revenue distribution by payment method |
| Target Achievement | Actual performance compared with budget |
| Item-Level Revenue | Revenue contribution by menu item |
| Category Revenue | Revenue grouped by food category |
| Upselling Revenue | Revenue generated through upselling |
| Average Upsell per Room | Average upselling revenue relative to rooms |

### Brand & Guest Experience

| Metric | Description |
|---|---|
| Guest Ratings | Overall guest review ratings |
| Platform Breakdown | Reviews grouped by Google, TripAdvisor and OTA platforms |
| Sentiment Trends | Changes in guest feedback sentiment |
| Review Response Rate | Proportion of reviews receiving responses |
| Checkout Count | Recorded guest departures |
| Review Rate | Guest review rate calculated using booking and review information |

### People Analytics

| Metric | Description |
|---|---|
| Workforce Headcount | Total employee count |
| New Joiners | Employees joining during a selected period |
| Employee Movement | Changes in workforce composition |
| Attrition Reasons | Categories of employee exits |
| Employees Trained | Number of employees attending training |
| Training Hours | Total recorded training hours |
| Training Sessions | Number of training sessions conducted |
| Training Attendance Rate | Training participation percentage |

### Property Performance

| Metric | Description |
|---|---|
| Guest Complaints | Number of recorded complaints |
| Complaint Categories | Classification of guest complaints |
| Resolution Status | Current complaint resolution state |
| Room Records | Room-related complaint information |

### Executive Review

| Metric | Description |
|---|---|
| Discussion Items | Total executive review items |
| Departmental Assignments | Department responsible for each item |
| Discussion Status | Current status of review items |

## 5. Data Modelling Documentation

The following details are pending schema inspection:

- Column names and data types
- Primary and foreign keys
- Table relationships
- Date and timestamp fields
- Partitioning and clustering
- Nullability and data-quality rules
- Metric calculation formulas
- Join conditions and aggregation logic

These details should be documented from actual BigQuery schemas and SQL queries rather than assumed.

## 6. Data Privacy

All public demonstrations must use sanitized data.

No production employee records, guest information, private transaction details, credentials, or confidential business identifiers should be included in this repository.

---

**Storage Platform:** Google BigQuery

**Documentation Scope:** 11 demonstration tables across two logical data domains.
