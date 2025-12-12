# E-Commerce-Checkout-Sales-Performance-Dashboard-
This is a self‑built e‑commerce analytics project created to practise Excel data modelling and Tableau dashboard design.

1. Project overview
Built a small e‑commerce dataset with website sessions, cart adds, orders and revenue for multiple months.

Designed a Tableau dashboard to track the checkout funnel, key KPIs and monthly revenue trends.

Focused on understanding where users drop off in the funnel and how revenue changes across quarters (Q1–Q4).

2. Data source
Tool: Microsoft Excel

Main fields:

month

sessions

cart_adds

orders

revenue

Data type: Dummy / self‑created numbers to simulate a small e‑commerce store.

Excel file is used as the primary data source and is connected directly to the Tableau workbook.

3. Metrics and formulas
In Excel / Tableau, the following KPIs are calculated:

Conversion rate (CR)

Formula: orders ÷ sessions

Cart abandonment rate (CAR)

Formula: 1 − (orders ÷ cart_adds)

Average order value (AOV)

Formula: revenue ÷ orders

Customer lifetime value (CLV)

Simplified formula based on average order value and an assumed repeat‑purchase factor (for learning purposes).

These calculations are implemented as calculated fields inside Tableau and used in the dashboard KPI cards.

4. Dashboard design (Tableau)
Tool: Tableau Public

Main workbook: Monthly_Q4_Spike.twbx

Key elements:

KPI cards showing CR, cart abandonment rate, AOV and CLV.

Monthly revenue line chart to compare performance across months.

Visual highlight showing a strong Q4 revenue spike (around 30–35% higher than Q1) to indicate seasonality and growth opportunities.

Simple layout focusing on readability and quick interpretation for a non‑technical stakeholder.

