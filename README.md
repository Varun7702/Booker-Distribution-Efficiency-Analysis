# Booker Distribution Efficiency Analysis

## Project Overview
This project aims to optimize the distribution process for Booker, a wholesale distributor handling thousands of weekly deliveries. Using dummy data provided, the analysis explores key areas to improve delivery efficiency, reduce costs, and mitigate financial risks associated with customer orders.

## Data Sources
The project utilizes four datasets:

- **Customer Data**: Information on store locations, delivery schedules, and credit limits.
- **Company Data**: Locations and capacity of distribution centers.
- **Orders Data**: Weekly customer orders, covering three historical weeks and one predicted week.
- **Product Data**: Product information, including cost per case.

## Objectives
- Assign delivery distribution centers (DCs) for new stores.
- Recommend efficient delivery schedules for stores lacking specified delivery days.
- Estimate orders with missing data and assess order patterns.
- Analyze instances of orders exceeding credit limits and assess financial risk.
- Recommend optimal daily capacity for each distribution center.
- Identify network efficiencies and propose cost-saving measures.

## Analysis Summary
- **Data Cleaning**: Initial checks for missing values and duplicates were performed, followed by data type adjustments.
- **Delivery DC Assignment**: Proposed DC allocations for new stores based on proximity.
- **Delivery Scheduling**: Analyzed order data to determine optimal delivery days for certain stores.
- **Credit Limit Risk Assessment**: Evaluated customers ordering above their credit limit.
- **Capacity Planning**: Proposed new daily capacities for each DC to balance demand.
- **Anomaly Detection**: Flagged unusual order patterns for investigation.

## Findings and Recommendations
- New delivery DCs were assigned to stores lacking an initial assignment.
- Optimal delivery days were proposed based on order frequency.
- Customers consistently exceeding credit limits were identified, and financial risk levels were estimated.
- Suggested network optimization strategies that could enhance cost efficiency.
"""
