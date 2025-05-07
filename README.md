# 🛍️ Retail Sales Data Analysis & Visualization

This project focuses on cleaning, exploring, and visualizing retail sales data from a Supermarket. Using Python for data preparation and Tableau for dashboarding, I derived key business insights to aid decision-making.

##  Problem Statement

The retail company wants to identify:
- Which product categories and sub-categories generate the most sales and profit
- Performance across regions and customer segments
- Patterns in shipping delays
- Factors influencing profitability

---

## Tools & Technologies

- **Python**: Data cleaning and EDA (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- **Tableau Public**: Interactive dashboard
---

## Data Cleaning (Python)

- Converted `Order Date` and `Ship Date` to datetime
- Created a new feature: `Shipping Time` (in days)
- Verified data types

---

## Exploratory Data Analysis

Key findings using visualizations:

- **Top Categories by Sales**: Technology > Office Supplies > Furniture
- **Most Profitable Sub-categories**: Copiers, Phones, Accessories
- **Regional Trends**:  
  - West leads in sales  
  - East generates the most profit  
  - Central has high sales but low profits

- **Shipping Patterns**:  
  - Most orders are delivered in 2–4 days  
  - Standard Class is the slowest

- **Sales vs. Profit**:  
  - Some high-sales items (e.g., Tables) have low/negative profit due to discounts

---

## Tableau Dashboard

The final interactive dashboard includes:
KPI Cards (Total Sales, Total Profit, Total Quantity, Total Discount)
Sales & Profit by category (Packed Bubbles)
Top customers in each region (Bar Chart)
Sales by Region (Pie Chart)
Profit by Sub-category (Bar Chart)

View Dashboard on Tableau Public https://public.tableau.com/views/SuperstoreSalesDashboard_17466127429820/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Key Insights & Recommendations

- Focus marketing on **Technology** and **Copiers**
- Reduce discounts on **Tables** to boost profit
- Improve delivery speed for **Standard Class**
- Investigate underperforming **South and Central** regions

---


## What I Learned

- Real-world data is messy, and so cleaning is critical.
- Data storytelling is just as important as the analysis.
- Tableau helps turn insights into action fast.
- Sales ≠ Profit; it pays to dig deeper.

---
