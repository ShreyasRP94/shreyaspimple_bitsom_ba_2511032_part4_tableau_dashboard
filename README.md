# shreyaspimple_bitsom_ba_2511032_part4_tableau_dashboard

# Retail Sales Executive Dashboard

## Business Problem Summary

The objective of this project is to develop an interactive executive dashboard for a retail company using Tableau. The leadership team requires a centralized view of business performance to monitor sales, profitability, customer behaviour, category performance, shipping efficiency, discount impact, and product returns.

The dashboard is designed to help business leaders quickly identify growth opportunities, operational risks, and areas requiring strategic intervention through interactive visualizations and KPI monitoring.

---

## Dataset Description

The project uses a fictional retail sales dataset containing order-level transactional data.

The dataset includes information such as:

* Order ID
* Order Date
* Customer ID
* Customer Segment
* Region and State
* Category and Sub-Category
* Sales
* Profit
* Discount
* Shipping Mode
* Delivery Days
* Return Flag
* Campaign Channel

The data enables analysis across financial performance, customer behaviour, logistics, and operational efficiency.

---

## Tableau Workbook Description

The Tableau workbook (`executive_dashboard.twbx`) contains:

### Executive Dashboard

A single interactive dashboard summarizing key business performance metrics.

### Individual Worksheets

1. Quarterly Sales Trend
2. Regional Performance
3. Category Profitability
4. Customer Segment Analysis
5. Shipping Performance
6. Discount vs Profit Analysis
7. Return Analysis

Additionally, KPI worksheets were created for:

* Total Sales
* Total Profit
* Profit Margin
* Return Rate

---

## Calculated Fields Created

The following calculated fields were created within Tableau to support dashboard analysis.

| Calculated Field      | Description                                                          |
| --------------------- | -------------------------------------------------------------------- |
| Profit Margin         | Profit divided by Sales                                              |
| Cost                  | Sales minus Profit                                                   |
| Average Order Value   | Total Sales divided by unique Order IDs                              |
| Return Rate           | Returned Orders divided by Total Orders                              |
| Shipping Delay Bucket | Categorizes delivery days into Fast, Standard, and Delayed shipments |
| Profit Category       | Classifies transactions as Profit, Loss, or Break Even               |
| Delivery Status       | Identifies shipments as On Time or Delayed                           |

These calculated fields were used throughout the dashboard for KPIs, tooltips, filtering, and visual analysis.

---

## Dashboard Components

The executive dashboard contains the following components:

### KPI Cards

* Total Sales
* Total Profit
* Profit Margin
* Return Rate

### Visualizations

* Quarterly Sales Trend (Line Chart)
* Regional Performance (Horizontal Bar Chart)
* Category Profitability (Bar Chart)
* Customer Segment Performance (Bar Chart)
* Shipping Performance (Horizontal Bar Chart)
* Discount vs Profit Relationship (Scatter Plot)
* Return Analysis (Bar Chart)

The dashboard follows a top-down executive layout beginning with KPI summaries, followed by trend analysis, performance analysis, customer insights, operational metrics, and business risk indicators.

---

## Filters and Interactions Used

The dashboard includes multiple interactive filters allowing users to explore data dynamically.

### Filters

* Region
* Category
* Customer Segment
* Order Date
* Ship Mode
* Campaign Channel

### Dashboard Actions

Interactive filter actions were implemented so that selecting values in major charts (such as Regional Performance or Category Profitability) automatically updates the remaining dashboard visualizations and KPI cards.

This enables users to perform drill-down analysis without navigating away from the dashboard.

---

## Key Business Insights

Several important business insights were identified from the dashboard:

* Sales remained relatively stable over time with a noticeable improvement in later quarters.
* Technology is the most profitable product category.
* Certain Furniture and Office Supplies sub-categories contribute comparatively lower profits.
* Customer segments generate similar sales volumes, although profitability varies.
* Higher discount percentages are associated with lower or negative profits.
* Standard shipping requires longer delivery times than premium shipping modes.
* Return rates differ across categories and customer segments, highlighting potential quality or customer experience issues.
* Profitability is influenced by a combination of pricing strategy, shipping performance, product mix, and return behaviour.

These insights support data-driven decision making across sales, marketing, operations, and product management.

---

## Dashboard Story Summary

The dashboard presents a complete business performance narrative for leadership.

It begins with high-level KPIs summarizing overall business health, followed by quarterly sales trends to assess revenue growth. Regional and category analyses identify where revenue and profit are generated, while customer segment analysis highlights purchasing behaviour.

The dashboard then explores operational drivers through shipping performance and investigates the relationship between discounts and profitability using a scatter plot. Finally, return analysis identifies areas where customer satisfaction or product quality may require attention.

Together, these visualizations help leadership understand current performance, identify business risks, and prioritize improvement opportunities.

---

## Assumptions and Limitations

### Assumptions

* The provided dataset is complete and accurately represents retail transactions.
* Return Flag values correctly indicate returned orders.
* Delivery Days accurately represent shipment duration.
* Profit and Sales values are assumed to be free from calculation errors.
* Average Order Value is calculated using unique Order IDs.

### Limitations

* The dataset represents historical transactions only and does not include forecasting.
* External factors such as competitor activity, inventory availability, customer satisfaction, or economic conditions are not included.
* Campaign effectiveness is analysed only using available transactional data.
* Customer lifetime value and repeat purchase behaviour are outside the scope of this dashboard.

---

## Screenshots Included

The following screenshots are included as part of the submission:

* `screenshots/full_dashboard.png`
* `screenshots/sales_trend_view.png`
* `screenshots/regional_performance_view.png`
* `screenshots/category_profitability_view.png`
* `screenshots/filter_interaction_view.png`

These screenshots demonstrate the completed dashboard, major visualizations, and interactive filtering functionality.

---

## Tools Used

* Tableau Public 2025.3 (Student Version)
* Microsoft Excel
* VS Code



---

## Project Outcome

The completed dashboard provides leadership with an interactive, business-friendly view of organizational performance. It combines financial, operational, and customer metrics into a single executive reporting solution that supports faster decision making and highlights actionable business opportunities.

