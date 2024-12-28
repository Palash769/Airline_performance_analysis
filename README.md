![airline dashboard](https://github.com/user-attachments/assets/8d4bcf25-cf40-43bc-a285-5df290132e2a)
# Airline_performance_analysis


## Description
This project involves creating an **Airline Performance Analysis Dashboard** in Power BI to assess key performance metrics of airlines. The dashboard provides insights into critical aspects such as flight delays, cancellations, on-time performance, and other operational statistics. The aim is to help stakeholders make informed decisions to enhance airline operations and customer satisfaction.


## Features
- **Interactive Visualizations**: 
  - Line charts, bar graphs, and pie charts for performance trends.
  - Slicers and filters for dynamic data exploration.

- **Key Performance Indicators (KPIs)**:
  - Average delay time per airline and route.
  - Cancellation rates and their reasons.
  - On-time performance percentage.

- **Drill-Down Functionality**:
  - Detailed analysis by airline, route, and time period.

- **Data Insights**:
  - Identification of patterns in delays and cancellations.
  - Impact of seasons and weather conditions on performance.


## Tools & Technologies
- **Power BI**: For data modeling, visualization, and dashboard creation.
- **Data Source**: Airline performance datasets.
- **DAX (Data Analysis Expressions)**: For calculated fields and KPIs.


## Files in the Repository
- `AirlinePerformanceAnalysis.pbix`: Power BI file containing the dashboard.

## Dataset Description
The dataset includes the following columns:
- `Airline Name`: Name of the airline.
- `Flight Number`: Unique identifier for each flight.
- `Origin` and `Destination`: Airports where flights begin and end.
- `Delay (Minutes)`: Delay time for each flight.
- `Cancellation Reason`: Reason for flight cancellation (e.g., weather, technical issues).
- `On-Time Status`: Boolean value indicating whether a flight arrived on time.


## Insights Derived
1. **Top Performing Airlines**:
   - Airlines with the best on-time performance.
   - Airlines with the lowest cancellation rates.

2. **Frequent Delay Causes**:
   - Routes or times prone to delays.
   - Common reasons for delays and cancellations.

3. **Operational Efficiency**:
   - Airports with the most efficient operations.
   - Time periods with the least delays.



## How to Use
1. Clone the repository to your local system:
   ```bash
   git clone https://github.com/Palash769/Airline_performance_analysis.git
