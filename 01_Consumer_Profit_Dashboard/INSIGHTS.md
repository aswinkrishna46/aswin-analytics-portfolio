# Consumer Profit Dashboard — Insights
> Project 01 — Retail Profitability Optimization  
> Data-driven insights using SQL + Power BI

## Business Objective  
Identify where the business is winning, where margin erosion occurs, and what strategic actions can improve profitability across segments, categories, and regions.

---

## Key Findings  

- Consumer segment is the primary profit engine, contributing the highest total profit.  
- Technology is the top category by profit ($531), followed by Furniture — both show strong margins.  
- EU West is the strongest region ($616 profit), driven by Technology + Consumer sales.  
- Office Supplies underperforms, contributing low profit across regions and segments.  
- February profit dropped sharply versus January, despite similar order volumes — indicating margin erosion, not demand decline.  
- Discount analysis shows that high-discount orders increased in February, and these orders contribute significantly less profit, confirming that discounting behavior directly caused the month-over-month decline.

---

## Root Cause Analysis  

The February decline is margin-driven, not volume-driven:

- Order volume was stable, but  
- Average Profit Per Order dropped, especially in Technology and Consumer/Home Office segments.  
- Discount band patterns reveal a shift toward higher-discount orders, which eroded margins even when sales remained steady.  
- Product mix also leaned toward lower-margin combinations.

This confirms that pricing and discount behavior — not customer demand — drove the February profit deterioration.

---

## Recommendations  

1. Strengthen Consumer + Technology strategy  
   - This combination drives the highest overall profit.  
   - Protect margins by tightening discount rules for key SKUs.

2. Increase Furniture order volume  
   - Strong per-order margins indicate room for profitable growth through promotions or bundled offers.

3. Repair Office Supplies performance  
   - Conduct SKU-level profitability review.  
   - Adjust pricing or discontinue consistently low-margin products.

4. Fix discount leakage  
   - Limit high-discount transactions that dilute margin, especially in Technology.  
   - Introduce discount ceilings and monitor discount performance monthly.  
   - Align promotional campaigns with profitability rather than pure volume.

5. Maintain Corporate segment efficiently  
   - Stable but low-volume; retain key accounts without heavy investment.

---

## Skills Demonstrated  

- SQL: joins, aggregations, time-series trend analysis  
- Power BI: multi-page storytelling, DAX (Avg Profit Per Order, discount segmentation), KPI design  
- Business analysis: identifying profit drivers, diagnosing margin erosion, understanding discount impact  
- Data storytelling: translating dashboards into actionable recommendations  

---

## Dashboard Screenshots  

### Executive Summary — Consumer Profit Dashboard
![Executive Overview Dashboard](./images/Segment%20Level%20Profit%20Dashboard.png)

### Segment × Category Performance
![Segment Category Dashboard](./images/Segment%20×%20Category%20Profit%20Analysis.png)

### Monthly Performance Analysis
![Monthly Analysis Dashboard](./images/Monthly%20Performance%20Analysis.png)

### Regional Performance Analysis
![Regional Performance Dashboard](./images/Regional%20Profit%20Strategy.png)

### Profit Drivers — EU West Deep Dive
![EU West Deep Dive](./images/EU%20West%20Deep%20Dive.png)

### Discount Strategy Profit Analysis
![Discount Strategy](./images/Discount%20Strategy%20Profit%20Analysis.png)

---

## Files in This Project  

- Consumer_Profit_Dashboard_v6_Aswin.pdf — full multi-page report  
- Power BI .pbix source file — available on request  

---

## Business Value  

This dashboard helps leadership understand where profit originates, why February’s margin collapsed, and which actions will drive the fastest improvement — across pricing, discounting, product mix, and regional strategy.
