# Pizza Sales Performance Dashboard

An interactive data analytics dashboard designed to monitor and analyze pizza restaurant sales performance, customer ordering behavior, and menu item trends. This project translates raw transactional logs into actionable business insights to streamline kitchen operations and optimize stock management.

## Dashboard Overview

<img width="1873" height="686" alt="Pizza Sales Dashbord" src="https://github.com/user-attachments/assets/0aa88378-d2e2-44a9-a265-0890eadcd7d8" />

The dashboard provides a highly visual, centralized overview of sales metrics, operating efficiency, and customer purchasing patterns across a single fiscal year (2015). By breaking down sales by time of day, month, size, and category, the dashboard helps operators easily pinpoint customer preferences and peak operational demands.

### Key Visualizations & Insights

* **Core KPIs**: Tracks three foundational business metrics at a glance: **Sum of Sales** (totaling 8,436), **Sum of Quantity** (511 items), and **Count of Customers** (499 unique visits).
* **Hourly Ordering Patterns**: Maps out order volumes per hour to identify peak operational times. Data peaks sharply in the evening around **5:00 PM** (72 orders) and maintains high activity during lunch hours (**12:00 PM - 1:00 PM**), while dropping significantly by 11:00 PM.
* **Monthly & Seasonal Trends**: Visualizes both total revenue and unique customer traffic month-by-month. Sales peak heavily during the summer months, with **June** (859) and **August** (858) leading revenue, closely matching customer traffic spikes.
* **Menu Breakdown**: Categorizes offerings into four distinct types (**Veggie**, **Classic**, **Supreme**, and **Chicken**). Veggie leads in overall sales volume (2,365), followed tightly by Classic (2,275).
* **Sizing Preferences**: Tallies orders based on portion size (**L, M, S, XL**). Large (L) pizzas dominate customer preference, driving a staggering 4,005 in volume, while Extra Large (XL) is the least popular (281).
* **Top 10 Performing Pizzas**: Identifies the most popular menu choices based on velocity. **The Classic Deluxe Pizza** ranks #1 (30 orders), closely followed by **The Pepperoni Pizza** (26 orders) and **The Four Cheese Pizza** (23 orders).

---

## Interactive Filters (Slicers)

Users can dynamically slice data across the canvas using the following components:
* **Pizza Category**: Filter by Chicken, Classic, Supreme, or Veggie.
* **Pizza Size**: Isolate trends by Large (L), Medium (M), Small (S), or Extra Large (XL).
* **Order Date (Timeline)**: Drill down into specific fiscal quarters (Q1, Q2, Q3, Q4) across the 2015 calendar year.

---

## Technical Metrics Defined

* `Sum of Sales`: Cumulative gross revenue generated from finalized orders.
* `Sum of Quantity`: Total volume of individual pizza units prepared and sold.
* `Count of Customer`: Total unique customer transactions processed.
