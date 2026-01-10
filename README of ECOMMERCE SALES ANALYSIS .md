This notebook analyzes an e‑commerce dataset using SQL queries executed via Python to extract business‑level insights across customers, orders, products, sellers, time, and revenue. The analysis moves beyond basic counts and focuses on growth, concentration, customer behavior, and revenue dynamics.

1. Customer & Geography Insights

Customers are distributed across multiple cities and states, with a clear concentration in a few high‑population states.

Some cities show higher average products per order, indicating stronger basket size and cross‑sell potential.

Customer distribution is uneven, meaning logistics, marketing, and seller onboarding should prioritize high‑density regions.

Business takeaway: Focus retention campaigns and faster delivery promises in top states/cities where customer density and order volume are highest.

2. Order Trends & Seasonality

Orders show monthly variation, with noticeable peaks during certain months in 2018.

Cumulative monthly sales consistently increase year‑over‑year, confirming overall platform growth.

Moving average of order values smooths short‑term noise and reveals more stable long‑term customer spending behavior.

Business takeaway: Plan promotions and inventory around high‑volume months and use moving averages for forecasting instead of raw daily sales.

3. Revenue & Category Performance

Revenue is highly concentrated in a limited number of product categories.

A small set of categories contributes a disproportionately large share of total revenue.

Category‑level contribution analysis highlights which categories truly drive the business versus those that add marginal value.

Business takeaway: Double down on top‑revenue categories for ads and seller acquisition; low‑contribution categories may need pricing or positioning changes.

4. Payment Behavior

A significant portion of orders are paid via installments.

Installment usage lowers purchase friction and enables higher‑value transactions.

Business takeaway: Installment options are not optional — they are a growth lever. Removing them would likely reduce conversion and order value.

5. Price vs Demand Relationship

Correlation analysis between product price and purchase frequency shows weak to moderate negative correlation.

Higher prices generally reduce purchase count, but not uniformly across all products.

Business takeaway: Price sensitivity varies by category. Blanket discounting is inefficient — apply category‑specific pricing strategies.

6. Seller Performance & Revenue Concentration

Revenue per seller is heavily skewed: a small number of sellers generate a large share of total revenue.

Seller ranking highlights dependence on top performers.

Business takeaway: Platform risk exists if top sellers churn. Introduce seller loyalty programs and diversify revenue across mid‑tier sellers.

7. Customer Value & Retention

Top customers contribute a disproportionately high share of yearly revenue.

Retention analysis (repeat purchase within 6 months) shows that not all acquired customers return.

Business takeaway: Acquisition without retention is wasteful. High‑value repeat customers should be targeted with loyalty rewards and personalized offers.

8. Growth Analysis

Year‑over‑year sales growth confirms business expansion but also shows variability across years.

Growth is not linear, indicating sensitivity to external factors (seasonality, promotions, market conditions).

Business takeaway: Growth should be monitored alongside customer retention and seller diversification, not revenue alone.

Final Conclusion

This analysis shows a classic e‑commerce pattern:

Revenue and sellers are highly concentrated.

A minority of customers and categories drive most value.

Installments and seasonality play a major role in sales volume.

Strategic focus areas: retention, top‑category optimization, seller risk reduction, and data‑driven pricing — not just raw growth metrics.
