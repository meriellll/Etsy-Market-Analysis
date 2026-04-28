
# Etsy Market Analysis — Identifying a Profitable Product Opportunity

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **TL;DR:** Analyzed 3,800+ Etsy listings to uncover a high-opportunity gap in a saturated market and define a data-driven product strategy.

## Table of Contents

- [Project Overview](#-project-overview)
- [Objective](#-objective)
- [Data](#-data)
- [Methodology](#-methodology)
- [Key Insights](#-key-insights)
- [Market Gap](#-market-gap)
- [Strategy](#-strategy)
- [Success Metrics](#-success-metrics)
- [Tools Used](#-tools-used)
- [Conclusion](#-conclusion)

**Project Overview**

This project analyzes ~3,800 Etsy listings to identify a high-opportunity niche and define a data-driven product strategy.

The goal was not just to explore the data, but to **translate insights into a clear business decision**.

---

**Objective**

- Identify a profitable niche within Etsy digital products  
- Understand demand vs competition dynamics  
- Define a strategic product positioning and pricing approach

## Data

| Feature | Description |
|--------|------------|
| Price | Listing price (USD) |
| Total Favorites | Number of users who favorited the listing (**demand signal**) |
| Total Reviews | Number of reviews (**proxy for conversions**) |
| Keyword | Search term used to find the listing |
| Product Name | Listing title |

**Methodology**

The analysis followed a structured approach:

### 1. Market Understanding
- Price vs demand analysis  
- Trend comparison (6m vs 12m)  
- Keyword & audience analysis  

### 2. Opportunity Identification
- Conversion analysis (what sells vs fails)  
- Pricing & competition mapping  
- Opportunity scoring  

---

## Key Insights

| Insight | Explanation |
|--------|------------|
| Low-price saturation | Most listings cluster between $2–$7 |
| Low conversions | Majority of listings have few or zero reviews |
| Structure wins | High-performing products use guides, lists, habit systems |
| Positioning > pricing | Competing on value is more effective than lowering price |
---

**Market Gap**

Analysis of price vs demand revealed:

- High competition clustered in low-price, low-performance listings  
- Very few competitors positioned in higher-value ranges  
- Some higher-priced listings still achieve strong demand  

This indicates a clear gap for **better-structured, higher-value products**

---

## Strategy

| Element | Decision |
|--------|---------|
| Niche | Weight loss / lifestyle tracking |
| Audience | Beginners seeking structure and simplicity |
| Positioning | Structured system (not generic planner) |
| Pricing | Launch: $5.99–$6.99 → Scale: $7.99–$9.99 |
---

## Success Metrics

| Stage | Target |
|------|--------|
| Month 1 | 4+ favorites (proof of interest) |
| Month 3 | 15+ favorites + 2 reviews (market average) |
| Month 6 | 36+ favorites + 5 reviews (top 10%) |


**Tools Used**

- Python  
- Pandas  
- Matplotlib  

---

**Key Takeaway**

This market is not limited by demand, but by **weak positioning and lack of structured solutions**.

---

**Notes**

This project focuses on **decision-making using data**, not just analysis.

The full product execution is intentionally not included.

**Market Gap Visualization**
![Market Gap](visuals/image.png) 

## Project Structure

```bash
Etsy-Market-Analysis/
│
├── README.md
├── analysis.ipynb
└── visuals/
    ├── market-gap.png
    └── price-analysis.png
