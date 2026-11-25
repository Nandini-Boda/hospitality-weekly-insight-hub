# Dashboard Modules

## 1. Overview

The Hospitality Weekly Insight Hub provides a unified business intelligence interface for monitoring hospitality performance.

The dashboard is organized into five major modules, each designed to address a specific business reporting requirement.

## 2. Revenue Analytics

### Objective
Provide visibility into financial and operational revenue performance across F&B and Front Office activities.

### Key Capabilities

- Total F&B revenue monitoring
- Order volume tracking
- Average Order Value analysis
- Daily revenue trends
- Payment method distribution
- Property-level performance comparisons
- Budget versus actual tracking
- Menu item and food category analysis
- Front Office upselling performance
- Upselling target monitoring
- Transaction-level upselling visibility

### Data Sources

- `fnb_sale_demo`
- `fnb_targets_demo`
- `fnb_item_sale_demo`
- `fo_upsell_demo`
- `fo_upsell_target_demo`

### Business Value

Enables management to monitor revenue performance, identify trends, evaluate target achievement, and understand revenue contribution across business activities.

## 3. Brand & Guest Experience

### Objective
Monitor guest reputation, feedback, and review performance.

### Key Capabilities

- Guest rating analysis
- Review platform comparison
- Guest sentiment trends
- Review response monitoring
- Checkout tracking
- Guest review-rate calculation

### Data Sources

- `sales_booking_demo`
- `Ratingsheet_demo`

### Business Value

Provides visibility into guest feedback and reputation performance, supporting service-quality monitoring and brand improvement initiatives.

## 4. People Analytics

### Objective
Provide workforce development and training visibility.

### Key Capabilities

- Employee training participation
- Total training hours
- Training sessions conducted
- Training category breakdown
- Training attendance monitoring

### Data Sources

- `training_attendance_demo`

### Business Value

Helps monitor workforce development activities and evaluate training participation.

## 5. Property Performance

### Objective
Monitor workforce movement and guest complaint performance.

### Key Capabilities

- Workforce headcount
- New employee joiners
- Employee movement
- Attrition and resignation reasons
- Guest complaint tracking
- Complaint category analysis
- Complaint resolution status
- Room-related complaint records

### Data Sources

- `hr_master_demo`
- `guest_complaints_demo`

### Business Value

Provides operational visibility into employee movement and guest experience issues, helping management identify areas requiring attention.

## 6. Points to Discuss

### Objective
Provide a structured view of executive review items and departmental follow-ups.

### Key Capabilities

- Executive discussion tracking
- Departmental responsibility assignment
- Discussion status monitoring
- Review-item visibility

### Data Sources

- `points_to_discuss_demo`

### Business Value

Supports management review processes by organizing discussion items and tracking departmental accountability.

## 7. Dashboard Design Principles

The dashboard is structured around the following principles:

**Centralized Reporting:** Business metrics are consolidated into one interface.

**Departmental Organization:** Information is grouped into functional modules.

**KPI Visibility:** Important business indicators are presented for quick monitoring.

**Performance Comparison:** Relevant metrics support comparisons across dates, targets, and properties.

**Executive Accessibility:** Reporting is organized to support management-level review.

## 8. Future Enhancements

Potential future enhancements include:

- Automated KPI alerts
- Exception-based performance monitoring
- Historical trend analysis
- Predictive revenue insights
- Hospitality market benchmarking
- Advanced guest sentiment analysis
- Automated executive reporting

---

**Platform:** Lovable

**Data Warehouse:** Google BigQuery

**Modules:** Revenue · Brand · People · Property · Points to Discuss
