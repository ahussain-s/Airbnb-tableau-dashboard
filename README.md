# Airbnb-tableau-dashboard
Built for current or aspiring NYC Airbnb hosts, this dashboard combines Airbnb listings, 311 complaint data, and MTA subway access to reveal which ZIP codes offer the strongest returns. Compare neighborhoods, assess risks, and make smarter, data-driven investment decisions in one of the world’s toughest short-term rental markets.
https://drive.google.com/drive/folders/1pjKFyJ1eZNb5DJHl8Ox7d2rNZ-mRwgJq?usp=drive_link 
**I have included my Tableau workbook and all datasets used in this project. You can access all files using the link below.**
# NYC Airbnb Market Intelligence: ROI Performance & Risk Assessment

A Tableau-powered visual analytics project that helps Airbnb hosts and investors identify the best ZIP codes in New York City for short-term rental success by combining ROI potential, neighborhood risk, and transit accessibility into one decision-making platform. 

---

## Overview

New York City is one of the world’s most competitive Airbnb markets, where profitability can vary dramatically by neighborhood. This project analyzes Airbnb listings, NYC 311 complaint records, housing prices, and MTA subway access to answer one critical question:

**Which NYC ZIP codes are truly worth investing in for Airbnb?**

This dashboard transforms raw market data into clear, actionable investment recommendations by evaluating:

* Expected Airbnb ROI
* Neighborhood complaint exposure
* Property cost efficiency
* Subway accessibility
* Borough-level performance differences

---

## Key Features

### ZIP Code Investment Intelligence

* ROI by ZIP code using Airbnb revenue vs. property values
* Dynamic “Strong Buy / Buy / Caution / Avoid” recommendations
* Complaint-adjusted risk grading
* ZIP-level investment scorecards

### Neighborhood Risk Assessment

* NYC 311 complaint analysis grouped into:

  * Housing & Building Issues
  * Noise & Disturbance
  * Regulatory & Vendor
  * Safety & Street Conditions
  * Transportation & Parking

### Transit Impact Analysis

* Subway line density per ZIP code
* MTA station access integrated into investment scoring
* Transit proximity as a rental viability predictor

### Interactive Dashboards

* Borough market overview
* ZIP code deep dive
* Ranked recommendation table
* Pentagon/Radar complaint visualization
* Hexbin Airbnb density maps

---

## Dashboard Structure

### Dashboard 1: ZIP Code Deep Dive

* ROI heat map by ZIP
* Pentagon complaint chart
* MTA station panel
* Comparison table
* Dynamic investment recommendation

### Dashboard 2: Market Overview

* Borough-level listing distribution
* Revenue comparison
* Entire apartment distribution
* Average pricing trends
* Neighborhood revenue treemap

### Dashboard 3: Recommendation Engine

* Ranked ZIP codes by investment grade
* ROI + Complaint + Transit combined analysis

---

## Data Sources

* **Inside Airbnb NYC Listings**
* **NYC Open Data 311 Complaints**
* **NYC Housing Price by ZIP Code**
* **MTA Subway Station Data**

---

### Advanced Tableau Features

* FIXED LOD expressions for ZIP-level ROI
* Parameter Actions for dynamic ZIP exploration
* Filter Actions for borough synchronization
* Custom Pentagon / Radar Chart using trigonometric coordinates
* Hexbin Maps using HEXBINX() / HEXBINY()

### Core Calculated Fields

```text
Occupancy Rate = MIN(([reviews_per_month] × 2 × 3) / 30, 0.70)

Annual Revenue = Occupancy Rate × Price × 365 × 0.97

ROI per ZIP = AVG(Annual Revenue / Average House Value)

Investment Grade:
- Strong Buy
- Buy
- Caution
- Avoid
```


## Key Insights

* Bronx ZIP codes delivered the highest ROI in the dataset
* Manhattan generated strong revenue but lower ROI due to property costs
* Subway-rich ZIP codes showed better occupancy and pricing
* Complaint type mattered more than complaint volume alone
* Strong Airbnb opportunities exist in every borough

---

## Tools & Technologies

* Tableau
* Python
* NYC Open Data
* Airbnb Market Data
* MTA Open Data
* Data Cleaning & Federated Joins
* Advanced Visual Analytics

---

## Why This Project Matters

This is more than an Airbnb dashboard — it’s a market intelligence system for smarter real estate decisions.

**For investors:** Find profitable ZIP codes
**For hosts:** Benchmark and optimize current properties
**For analysts:** Explore urban profitability patterns

---



---

**Built for data-driven Airbnb investing in NYC.**
