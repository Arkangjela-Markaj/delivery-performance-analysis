# Delivery Performance Analysis

## Project Overview
A delivery company wants to reduce failed deliveries by understanding which zones, vehicle types, times of day and drivers are underperforming — and why. This project analyzes 10,000 delivery records to uncover actionable insights for operations teams.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn) — data cleaning and analysis
- SQL (SQLite) — business queries and aggregations
- Tableau Public — interactive dashboard

## Key Findings
- **North zone** has the highest failure rate at 15.83%, nearly 2 points above the best performing West zone at 14.02%
- **Cars at late night** have the best success rate at 89%, while vans at late night perform worst at 82%
- **Driver performance varies dramatically** — top drivers achieve 92% success while the worst hit only 77%, a 15 point gap that signals a training opportunity
- **11am is surprisingly the worst hour** for deliveries, not morning rush hour as expected

## Recommendations
1. Investigate root causes in the North zone — higher failure rates aren't explained by delays alone
2. Reduce van assignments during late night shifts or provide additional support
3. Study what top drivers (84, 82, 15) do differently and build a training program around it

## Live Dashboard
[View Interactive Tableau Dashboard](https://public.tableau.com/views/DeliveryPerformanceAnalysis_17756885027360/DeliveryPerformanceDashboard)

## Files
- `delivery_performance_analysis.ipynb` — Python/Pandas analysis
- `delivery_sql_analysis.ipynb` — SQL queries and business questions
- `zone_failure_rate.csv` — failure rate by zone
- `top_drivers.csv` — top 10 driver performance
- `bottom_drivers.csv` — bottom 10 driver performance
- `worst_hours.csv` — worst performing hours
- `zone_vehicle_summary.csv` — zone and vehicle type breakdown
