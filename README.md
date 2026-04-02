# Retail Inventory Optimization Analysis

## Overview
This project analyzes inventory inefficiencies across a 10-store retail chain, "Super Shopper". The business faces widespread stockouts and overstocks, impacting revenue, customer satisfaction, and operational efficiency.

The analysis focuses on three core business functions:
- Warehouse Operations
- Point of Sale (POS)
- Accounting

---

## Business Problem
Super Shopper is experiencing:
- Frequent stockouts of high-demand products
- Overstocking of low-demand products
- Inefficient reorder processes across stores

These issues result in:
- Lost sales revenue
- Increased waste
- Poor customer experience

---

## Key Insights

### Inventory Issues
- 44% of products experienced stockouts
- Products were unavailable ~38% of the time over an 8-week period
- Multiple products experienced **consecutive stockout weeks**, indicating supply chain delays

### Lost Revenue (POS Analysis)
- Estimated **$3,675 in lost sales** over 8 weeks (Store 2)
- No single week without stockouts across the store

### Overstocking
- Several products showed **zero movement** (dead stock)
- Inefficient use of shelf space and capital

### Accounting Impact
- 60% of products required restocking
- Total reorder cost: $820
- Expected profit: $164 (20% margin → low tolerance for inefficiency)

---

## Root Cause
- Static, one-size-fits-all reorder points
- Poor alignment between warehouse and store-level demand
- Delays in reordering and fulfillment processes

---

## Recommendations

### 1. Dynamic Inventory Forecasting
- Shift from static to **store-level demand forecasting**

### 2. Adjust Reorder Points
- Increase reorder thresholds for high-demand products
- Reduce reorder levels for low-demand products

### 3. Improve Supply Chain Responsiveness
- Account for delays by triggering earlier reorders

### 4. Dead Stock Management
- Reduce inventory for non-moving products
- Reallocate shelf space to high-performing items

---

## Tools & Skills Demonstrated
- Data Analysis
- Inventory Optimization
- Business Analysis
- Excel-based modeling
- Data storytelling

---

## Project Structure
- `/docs` → Full case study reports
- `/visuals` → Charts and heatmaps
- `/data` → Source datasets (if available)

---

## Future Improvements
- Rebuild analysis using Python (pandas)
- Automate inventory forecasting
- Create interactive dashboards (Tableau / Power BI)