# Hospitality Weekly Insight Hub

An interactive Business Intelligence platform designed to bring hospitality performance metrics, operational KPIs, and executive insights into a unified dashboard.

## Overview

Hospitality Weekly Insight Hub is an analytics application that consolidates business performance data across multiple operational functions into a centralized reporting interface.

The platform connects Google BigQuery with an AI-assisted dashboard interface built using Lovable, enabling structured data access, automated reporting, KPI monitoring, and interactive business analysis.

The project focuses on simplifying fragmented reporting workflows and providing management with a unified view of business performance.

## Key Features

### 1. Revenue Analytics
- Revenue and order performance monitoring
- Average Order Value (AOV)
- Daily sales trends
- Payment mode analysis
- Property-level comparisons
- Budget versus actual performance
- Menu item and food category analysis
- Front Office upselling performance

### 2. Brand & Guest Experience
- Guest review monitoring
- Overall rating analysis
- Review platform breakdown
- Guest sentiment trends
- Review response rates
- Booking and checkout metrics

### 3. People Analytics
- Employee headcount monitoring
- Training sessions conducted
- Employee training hours
- Training attendance rates
- Learning category analysis

### 4. Property Performance
- Workforce movement
- New employee joiners
- Employee attrition analysis
- Resignation reason tracking
- Guest complaint monitoring
- Complaint category and resolution status

### 5. Executive Review
- Departmental discussion tracking
- Management review items
- Department assignments
- Discussion status monitoring

## Technology Stack

| Category | Technology |
|---|---|
| Dashboard Development | Lovable |
| AI-Assisted Development | Generative AI |
| Data Warehouse | Google BigQuery |
| Data Access | Lovable Connector Gateway |
| Data Querying | BigQuery queries |
| Data Visualization | Interactive dashboards |

## Data Architecture

The application uses Google BigQuery as its centralized data source.

The portfolio demonstration architecture consists of two logical data domains:

**Executive Analytics**
- F&B sales
- Sales bookings
- Revenue targets
- Upselling
- HR workforce
- Training attendance
- Guest complaints
- Executive discussion tracking

**F&B Guest Experience**
- Guest ratings
- Review platforms
- Rating trends
- Response monitoring

The documented demonstration environment contains 11 BigQuery demo tables across these two domains.

All dashboard sections retrieve their data from BigQuery through a server-side connector gateway.

## Dashboard Modules

| Module | Primary Focus |
|---|---|
| Revenue | Financial and sales performance |
| Brand | Guest experience and reputation |
| People | Workforce and training |
| Property | Operational and employee metrics |
| Points to Discuss | Executive follow-up and accountability |

## Repository Structure

```text
hospitality-weekly-insight-hub/
│
├── README.md
│
├── docs/
│   ├── architecture.md
│   ├── data-dictionary.md
│   └── dashboard-modules.md
│
├── screenshots/
│   ├── revenue/
│   ├── brand/
│   ├── people/
│   ├── property/
│   └── executive-review/
│
└── LICENSE
```

## Project Objectives

- Centralize hospitality business reporting.
- Improve visibility into departmental KPIs.
- Reduce fragmented reporting workflows.
- Enable structured data-driven decision-making.
- Provide management with consolidated performance insights.
- Establish a scalable foundation for advanced analytics.

## Future Enhancements

- Automated KPI alerts and notifications.
- Advanced historical trend analysis.
- Predictive business analytics.
- Hospitality market benchmarking.
- Advanced performance monitoring.
- Additional executive intelligence features.

## Security & Data Privacy

This portfolio project is intended to use sanitized demonstration data.

- No production credentials are published.
- No confidential business records are included.
- No personal employee or guest information is exposed.
- Cloud project identifiers and private connection configurations are excluded.

## Project Status

Documentation and portfolio preparation in progress.

Source code publication and reproducible deployment instructions will be added after source-code access, ownership permissions, and security reviews are completed.

---

**Built with:** Google BigQuery · Lovable · AI-Assisted Development

*An interactive approach to hospitality business intelligence.*
