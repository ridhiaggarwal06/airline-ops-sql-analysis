# Airline operations analysis using SQL

This project highlights how end-to-end database development and SQL analysis can turn raw operational data into actionable strategies for improving efficiency, profitability, and customer satisfaction.

- Objective:
The project required building a complete database solution from scratch. Key goals included:
  - Designing a normalised schema that accurately reflected flights, routes, costs, aircraft, and transactions.
  - Generating synthetic but realistic datasets to simulate airline operations.
  - Writing SQL queries to extract meaningful business insights such as route profitability, seat occupancy, peak travel days, and underutilised aircraft.


Process:
- Database Setup
  - Built a normalised schema (3NF) with six core entities: flights, aircraft, routes, airports, transactions, and costs.
  - Enforced primary/foreign keys and referential integrity to ensure clean, reliable relationships.

- Data Cleaning & Synthetic Data Generation
  - Generated 500+ records per entity using Mockaroo, with airline-specific rules for pricing, demand patterns, and seat ratios.
  - Cleaned inconsistencies (overbooking, missing values, date mismatches) using SQL validation and Python scripts.
  - Ensured realistic business rules: e.g., economy-to-business seat ratio of 3:1, and dynamic pricing multipliers for peak travel days.

- Exploratory Data Analysis (EDA)
  - Ran SQL queries to explore demand patterns, revenue by route, cost structures, and aircraft utilisation.
  - Used aggregations and joins to uncover insights linking operational data with financial outcomes.
 

- Key Insights
  - High-Demand Routes: Tokyo, Barcelona, and Paris consistently showed the strongest bookings and revenues.
  - Seat Occupancy: Paris flights had the highest fill rates, pointing to strong demand on short-haul routes.
  - Peak Travel Days: Wednesdays and Thursdays emerged as peak booking days.
  - Underutilised Aircraft: Two aircraft models (A380 and A320) were flown only once a month — cost–revenue analysis suggested reallocating them to profitable routes.
  - Financial Snapshot: The synthetic dataset produced ~£78M in revenue with £22M in operational costs across 138k transactions.
 


The project shows how structured data design, cleaning, and exploratory analysis can provide airlines with actionable insights:
- Optimise fleet allocation by redeploying underutilised aircraft.
- Introduce dynamic pricing strategies to capitalise on peak travel days.
- Increase flight frequency on profitable routes to grow revenue.
- Support long-term efficiency by continuously aligning costs vs revenues at the route level
