# Supplier Replenishment Risk Dashboard

# **Overview**

The Supplier Replenishment Risk Dashboard is a Supply Chain Analytics project developed to monitor supplier dependency, replenishment pressure, reorder risks, and procurement exposure using Excel-based analytics and dashboard reporting.

This project transforms raw supply chain data into actionable business intelligence that supports procurement optimization, inventory continuity, supplier risk monitoring, and operational decision-making.

The dashboard helps businesses identify:

- Critical reorder risks
- Supplier dependency exposure
- Understocked categories
- Procurement pressure points
- Replenishment inefficiencies
- Inventory supply gaps
- High-risk SKUs requiring urgent action

---

##  Project Objectives
The main objective of this project is to evaluate replenishment performance and supplier-related risks across inventory categories.

Key goals include:

- Monitor inventory against reorder demand
- Identify products below reorder thresholds
- Analyze supplier SKU concentration
- Detect understocked categories
- Evaluate procurement pressure across categories
- Assess replenishment cycle efficiency
- Improve supplier risk visibility
- Support data-driven procurement decisions

- **180 Critical Reorder SKUs** identified (operating below 50% of reorder threshold)
- **$305,485** Total Reorder Value at risk
- Identifies high-risk categories and supplier concentration vulnerabilities

---

## Business Problem

Many organizations struggle with inventory shortages, delayed replenishment, supplier dependency, and inefficient procurement planning.

Without proper monitoring:

- Critical SKUs fall below reorder levels
- Supplier disruptions create operational downtime
- Procurement becomes reactive instead of proactive
- Working capital becomes tied up in inefficient replenishment cycles
- Demand spikes result in stockouts and lost sales

This dashboard was developed to provide visibility into these operational risks and support proactive supply chain management.

---

##  Methodology

### 1. Data Collection

The dataset was sourced from **Kaggle** and includes comprehensive supply chain information:

- **Product Information**
- **Supplier Information**
- **Stock Quantities**
- **Reorder Levels**
- **Sales Volume**
- **Inventory Turnover Rates**
- **Product Status**
- **Pricing Information**

### 2. Data Cleaning & Preparation

All data preparation was performed directly in **Microsoft Excel**:

- Converted raw data into an **Excel Table** for structured referencing and dynamic updates
- Standardized and formatted date columns
- Reviewed data structure, completeness, and consistency
- Removed or handled inconsistencies for reliable analysis

### 3. Feature Engineering (Helper Columns)

Additional calculated columns were created to enhance analytical capabilities:

| Helper Column              | Purpose |
|---------------------------|---------|
| **Turnover Rate Distribution** | Groups inventory turnover into performance ranges |
| **Revenue**                | Calculates product revenue (`Sales Volume × Unit Price`) |
| **Turnover Band**          | Categorizes inventory movement performance |
| **Total Reorder Value**    | Measures total replenishment cost exposure |
| **Reorder Value**          | Calculates reorder cost per SKU |

These engineered fields significantly improve the ability to analyze:
- Inventory health
- Replenishment exposure
- Turnover performance
- Revenue contribution by product/SKU

---

## Dashboard Analysis

### 1. Reorder Level vs Current Stock Analysis
Overall inventory is slightly above reorder thresholds, but **category-level gaps** exist.

**Key Findings:**
- **Grains & Pulses** and **Beverages** are operating below reorder requirements → high stockout risk
- **Fruits & Vegetables** has the highest inventory exposure and reorder demand
- **Oils & Fats** shows the best stock-to-reorder balance

### 2. Critical Reorder Risk Analysis
**180 SKUs** are operating below 50% of their reorder threshold.

> This represents a significant operational vulnerability requiring immediate attention.

### 3. Supplier Dependency Analysis

**Top Suppliers by SKU Count:**

| Supplier | SKU Count |
|----------|-----------|
| Katz     | 12        |
| Meevee   | 10        |
| Quatz    | 9         |

High concentration under a few suppliers increases risk of delays, price hikes, or disruptions.

### 4. Replenishment Pressure by Category

**Highest Reorder Demand Categories:**

| Category              | Reorder Quantity |
|-----------------------|------------------|
| Fruits & Vegetables   | 16,505           |
| Dairy                 | 9,286            |
| Grains & Pulses       | 8,839            |

---

## Strategic Recommendations

### Immediate Actions
- Trigger emergency replenishment for the 180 critical SKUs
- Prioritize **Grains & Pulses** and **Beverages**
- Set up automated reorder alerts

### Supplier Risk Mitigation
- Develop backup suppliers for high-risk SKUs
- Introduce supplier performance scorecards
- Reduce SKU concentration per supplier

### Procurement & Inventory Optimization
- Implement category-specific reorder policies
- Introduce safety stock for critical items
- Shift toward demand-driven replenishment

---


## Dataset Information

- **Source**: Supply Chain Dataset (Kaggle)
- **Contents**: Product, Supplier, Stock, Reorder Levels, Procurement, and Sales data


---

## Conclusion

This Supplier Replenishment Risk Dashboard demonstrates how data-driven procurement and replenishment analysis can improve inventory availability, identify supplier dependency risks, and strengthen replenishment planning across the supply chain.
The insights generated from the dashboard provide a strong foundation for reducing stockout exposure, improving supplier risk visibility, optimizing procurement decisions, and ensuring more consistent inventory continuity through proactive supply chain management.

---

