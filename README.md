# Hospitality Revenue Insights Project

## Overview
This project analyzes revenue insights within the hospitality industry using booking data, date dimensions, and key performance metrics. It offers visual and tabular insights into occupancy rates, revenue trends, and booking patterns.

## Data Files
1. **dim_date.csv**: Contains date information for time-based analysis.
2. **fact_bookings.csv**: Holds booking transaction data with revenue and occupancy details.
3. **metrics list.xlsx**: Provides definitions and calculations for key metrics used in the analysis.

## Key Insights
- **Revenue Trends**: Analyzed by week, month, and platform.
- **Occupancy Rates**: Insights by city, room class, and day type.
- **Booking Channels**: Distribution of bookings across platforms.
- **Property Performance**: Evaluations based on revenue, occupancy, and cancellation rates.

## Usage Instructions
1. Load the data files into your analysis environment.
2. Use the provided Power BI or data visualization tools to explore dashboards.
3. Follow the metrics definitions from `metrics list.xlsx` for consistent calculations.

## Prerequisites
- Python (for data preprocessing)
- Power BI (for visualizations)
- Libraries: pandas, matplotlib, seaborn

## Example Code for Data Loading
```python
import pandas as pd

# Load data files
date_data = pd.read_csv('dim_date.csv')
bookings_data = pd.read_csv('fact_bookings.csv')

# Display sample data
print(date_data.head())
print(bookings_data.head())
```

## Visualizations and Dashboards
1. **Revenue by City**
   - Visualization of revenue distribution across major cities.
2. **Booking % by Platform**
   - Shows the share of bookings from different platforms.
3. **Occupancy by Room Class**
   - Highlights the occupancy rate for room classes like Standard, Premium, etc.

## Contribution Guidelines
- Fork the repository.
- Create feature branches for enhancements.
- Submit pull requests with clear descriptions.


Thank you for exploring revenue insights with us!
