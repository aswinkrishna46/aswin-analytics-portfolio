# Manufacturing FP&A Performance Analysis

## Objective
This project demonstrates FP&A-style financial analysis using Power BI, focusing on
**Actual vs Budget performance**, **variance analysis**, and **operating profit bridge logic**
in a manufacturing context.

The goal is to showcase analytical thinking, financial modeling discipline, and
executive-ready data storytelling — not just visual design.

---

## Tools & Technologies
- Power BI Desktop
- DAX (measures-based calculations)
- Star schema data modeling
- GitHub for versioned portfolio presentation

---

## Business Questions Answered
1. Are we ahead or behind budget on Operating Profit?
2. How does Actual performance trend against Budget over time?
3. What are the primary drivers of Operating Profit variance (Revenue, COGS, Opex)?
4. How can executives quickly interpret performance using clean, focused visuals?

---

## Dataset
- **Type:** Synthetic manufacturing FP&A dataset
- **Scope:** Monthly financials (Actuals and Budget)
- **Grain:** Month-level financial performance
- **Note:** Data is intentionally synthetic; emphasis is on **correct FP&A logic and modeling patterns**

---

## Report Structure

### Page 1 — Operating Performance Overview
- Actual vs Budget Operating Profit trend
- Monthly variance visualization
- Executive KPIs (YTD focus)
- Interactive slicers and context-aware tooltips

### Page 2 — Operating Profit Variance Bridge
- Waterfall bridge explaining variance drivers:
  - Revenue impact
  - COGS impact
  - Opex impact
- Designed for FP&A-style root cause analysis

*(A tooltip page is used internally to enhance interaction and is not a standalone analysis page.)*

---

## Key Measures (Conceptual)
- Actual Revenue, COGS, Opex
- Budget Revenue, COGS, Opex
- Operating Profit (calculated as a measure)
- Variance and Variance %
- Bridge impact measures for variance explanation

All derived metrics are implemented as **measures**, not stored columns.

---

## Design & Modeling Principles
- Measures-only approach for profitability metrics
- Clean separation between Actual and Budget scenarios
- Executive-first layout: summary → explanation
- Interaction design that avoids accidental filtering

---

## Known Limitations
- Cost-center-level deep dives are intentionally excluded due to the synthetic nature of the data.
- The focus of this project is **FP&A reasoning and reporting structure**, not operational cost allocation realism.

A future project will address cost-center and product-level profitability using more realistic datasets.

---

## Screenshots
*(Add 2–3 screenshots in the `/screenshots` folder and link them here)*

---

## Why This Project Matters
This dashboard reflects how FP&A teams evaluate performance:
- Start with high-level results
- Explain variance drivers clearly
- Present insights in a concise, executive-friendly format

It is designed as a **portfolio-grade FP&A analytics project** rather than a generic dashboard.

