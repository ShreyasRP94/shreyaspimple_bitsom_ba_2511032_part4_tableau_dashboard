# Chart Selection Justification

## 1. Quarterly Sales Trend

**Business Question:** How are sales changing over time?

**Chart Type:** Line Chart

**Why Appropriate:** A line chart clearly displays trends and seasonality across sequential quarters.

**Visual Encoding:**

* X-axis: Order Date (Quarter)
* Y-axis: Sales
* Labels: Quarterly Sales
* Tooltip: Profit, Profit Margin

**Design Principles Applied:**

* Chronological ordering
* Minimal clutter
* Consistent blue colour for sales
* Clear value labels

**Mistake Avoided:** Did not use bars or pie charts for time-series analysis.

---

## 2. Regional Performance

**Business Question:** Which regions contribute the most sales and profit?

**Chart Type:** Horizontal Bar Chart

**Why Appropriate:** Horizontal bars allow quick comparison across regions and simplify ranking.

**Visual Encoding:**

* Length: Sales
* Colour: Profit
* Tooltip: Profit Margin, Return Rate

**Design Principles Applied:**

* Descending sort
* Consistent formatting
* Clear comparison

**Mistake Avoided:** Avoided maps because exact value comparison is easier with bars.

---

## 3. Category Profitability

**Business Question:** Which categories and sub-categories generate the highest profit?

**Chart Type:** Horizontal Bar Chart

**Why Appropriate:** Enables direct comparison across categories and highlights profit concentration.

**Visual Encoding:**

* Length: Profit
* Colour: Profit Category
* Tooltip: Sales, Profit Margin

**Design Principles Applied:**

* Sorted values
* Consistent colour usage
* Business-friendly labels

**Mistake Avoided:** Avoided pie charts because many sub-categories reduce readability.

---

## 4. Customer Segment

**Business Question:** How do customer segments compare in terms of sales performance?

**Chart Type:** Bar Chart

**Why Appropriate:** Simple categorical comparison suitable for three customer segments.

**Visual Encoding:**

* Height: Sales
* Tooltip: Profit, Average Order Value, Return Rate

**Design Principles Applied:**

* Minimal clutter
* Consistent colours
* Clear labels

**Mistake Avoided:** Avoided stacked charts that would reduce comparison accuracy.

---

## 5. Shipping Performance

**Business Question:** Which shipping mode has the longest delivery time?

**Chart Type:** Horizontal Bar Chart

**Why Appropriate:** Average delivery time is easily compared across shipping modes.

**Visual Encoding:**

* Length: Average Delivery Days
* Tooltip: Return Rate, Profit Margin

**Design Principles Applied:**

* Logical sorting
* Simple layout
* Operational focus

**Mistake Avoided:** Avoided misleading stacked averages.

---

## 6. Discount vs Profit

**Business Question:** How does discount influence profitability?

**Chart Type:** Scatter Plot

**Why Appropriate:** Scatter plots are the best choice for identifying relationships between two numeric variables.

**Visual Encoding:**

* X-axis: Profit
* Y-axis: Discount
* Colour: Profit Category
* Size: Sales
* Detail: Order ID

**Design Principles Applied:**

* Bubble size encodes transaction value
* Colour distinguishes profitable and loss-making orders
* Rich tooltips improve exploration

**Mistake Avoided:** Avoided aggregating data into only a few points by plotting individual orders.

---

## 7. Return Analysis

**Business Question:** Which categories and customer segments have the highest return rates?

**Chart Type:** Bar Chart

**Why Appropriate:** Bar charts allow straightforward comparison of return rates across business dimensions.

**Visual Encoding:**

* Length: Return Rate
* Colour: Customer Segment
* Filter: Region

**Design Principles Applied:**

* Percentage formatting
* Clear category comparison
* Interactive filtering

**Mistake Avoided:** Avoided misleading visual scales and ensured return rates were presented clearly.

---

# Overall Dashboard Design Principles

The dashboard follows key visualization principles by using appropriate chart types, maintaining consistent colour usage, providing interactive filters and dashboard actions, reducing unnecessary clutter, applying meaningful sorting, and presenting information in a logical executive hierarchy. The layout guides users from high-level KPIs to sales trends, regional and category performance, customer behaviour, operational efficiency, and business risks, enabling leadership to move naturally from summary metrics to detailed analysis.
