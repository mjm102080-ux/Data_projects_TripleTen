# SUPERSTORE SALES & RETURNS ANALYSIS

### 🔗 [View the full interactive dashboard on Tableau Public →](https://public.tableau.com/app/profile/mark.meehan/viz/Sprint5Superstore/Story12?publish=yes)

## Overview

- An interactive Tableau analysis of a national retail dataset, built to uncover what drives product returns and to give executive leadership a clear, prioritized action plan. The project moves from raw sales-and-returns data through root-cause diagnosis to concrete, owner-assigned recommendations — a dashboard a CEO could open and act on, not just look at. It demonstrates the full BI workflow: data exploration, building linked visualizations, separating genuine signal from noise, and translating findings into business decisions.

## Key Findings

The analysis identified three root causes behind the returns problem:

1. **Repeat high-rate returners** — a concentrated group of multi-order customers returning 80–90% of their purchases. The pattern holds even after accounting for order volume, marking it as a behavior pattern rather than statistical noise.
2. **A West Coast operational cluster** — Utah, California, and Oregon show the highest state-level return rates in the country, forming a contiguous cluster that points to an operational rather than a product cause.
3. **Seasonal sub-category hot spots** — specific cells spike far above the category average (Copiers in August 67%, Machines in December 67%, Fasteners in October 65%, Appliances in August 55%). The takeaway: fix the cells, not the categories.

A key analytical distinction runs through all of this: some return spikes are **product problems** (return rates climb without any matching sales increase — a signal of quality, fit, or expectation issues), while others are **volume problems** (returns rise alongside sales — an operational capacity issue, not a product defect).

## Functionality

- The Tableau story walks through a guided analysis: Sales vs. Returns, Root Causes, recommended Actions, how to use the dashboard, and Next Steps with success criteria.
- An interactive dashboard lets the user drill down by sub-category, state, and customer cohort, with filters for Buyer Type and order count.
- Five prioritized, owner-assigned actions translate the findings into a leadership plan, from a customer behavior review to establishing return rate as a standing executive KPI.

## Recommended Actions

| # | Action | Owner | Timeline |
|---|--------|-------|----------|
| 1 | Launch a customer behavior review of chronic high-rate returners; investigate fraud, wardrobing, and expectation mismatches | Customer Success | 30 days |
| 2 | Audit West Coast fulfillment operations across the Utah–California–Oregon corridor | Operations | 60–90 days |
| 3 | Fix quality/fit issues on Copiers, Machines, Fasteners, and Supplies via clearer specs and pre-purchase guidance | Product & Marketing | 60 days |
| 4 | Prepare operationally for volume-driven return surges in the back-to-school season | Operations & Customer Service | Before August |
| 5 | Establish return rate as a standing executive KPI with sub-category, state, and cohort drill-downs | Analytics | 30 days |

## Images

[![Image](returns-heatmap.png)](returns-heatmap.png) [![Image](customer-returns.png)](customer-returns.png) [![Image](returns-map.png)](returns-map.png)

## Technologies

- Tableau Public — interactive story with multiple linked dashboards (heat map, customer ranking, choropleth map), calculated fields, and drill-down filters.

## How to View

- No installation or setup is required. The project is published on Tableau Public and runs in any modern web browser. Open the [live dashboard](https://public.tableau.com/app/profile/mark.meehan/viz/Sprint5Superstore/Story12?publish=yes), then use the navigation tabs at the top of the story to move between sections, and the interactive filters to drill down into the data yourself.

## Roadmap / Next Steps

A proposed 90-day implementation plan to act on the findings:

- **Days 1–30:** Launch the customer behavior review (Action 1) and deploy the KPI dashboard (Action 5).
- **Days 31–60:** Begin the pre-purchase experience overhaul (Action 3) and scope the West Coast audit (Action 2).
- **Days 61–90:** Finalize the August preparation plan (Action 4) and deliver an initial impact readout.

**Success criteria (measured in Q3 2026):**
- A 10–15% reduction in the August return spike
- West Coast state return rates moving toward the national average
- A measurable decline in repeat high-rate returner volume

## Notes

This project was completed as part of the Data Analytics program at TripleTen Bootcamp.
