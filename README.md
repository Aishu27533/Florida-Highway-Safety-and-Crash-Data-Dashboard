# Florida Highway Safety and Crash Data Dashboard

## Project Overview
This project uses one month of crash data from the **Florida Department of Highway Safety and Motor Vehicles** to create an interactive Tableau dashboard. It provides insights into the number of crashes, vehicle types involved, driver demographics, regional variations, and interesting trends in the data.

## Data Source
- **Event Table**: Details about crash incidents.
- **Driver Table**: Driver information.
- **Vehicle Table**: Vehicle information.

The data is structured with `report_number` as the key for joining the tables.

## Key Features
1. **Crash Count**: Displays the total number of crashes during the one-month period.
2. **Vehicle Type Analysis**: Identifies the most frequent vehicle types involved in crashes.
3. **Driver Demographics**: Analyzes driver factors such as age and gender.
4. **Regional Crash Variations**: Highlights regions with the highest crash rates.
5. **Exploratory Insights**: Reveals trends like peak crash times and other patterns.

## Tools and Technologies
- **Tableau** for data visualization
- **Outer Join**: Between Event, Driver, and Vehicle tables based on `report_number`
- **Data Dictionary**: For translating table values.

## Results and Insights
- **Crash Visualization**: Total crashes and patterns across demographics and regions.
- **Vehicle Insights**: Most involved vehicle types.
- **Driver Insights**: Demographics correlated with crash occurrences.
- **Regional Analysis**: Areas with higher crash rates highlighted.

## Installation Instructions
1. Download the project files from this repository.
2. Open the Tableau workbook (`.twb` or `.twbx`) in Tableau Desktop.
3. Refresh the data source if necessary.
4. Explore the interactive dashboard.

## Future Work
- Integration of real-time data for ongoing analysis.
- Deeper exploration of crash severity and contributing factors like weather.

