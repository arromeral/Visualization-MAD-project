# Visualization-MAD-project
<p align="center">
  <img width="1000" height="300" src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/92d57008-3786-48a3-aa5d-2a64b90d1f03">
</p>

## Description & Contents
This repository contains a data visualization project created using Power BI, focusing on analyzing flights departures from Adolfo Suárez Madrid-Barajas Airport over the past year. The visualization consists of two interactive dashboards providing detailed insights into various aspects of flights, correlating flight data, METAR weather reports, and EUROCONTROL airport statistics.

### Key Features:
**1. General Analysis Dashboard:**

  - Explore popular destinations.
  - Analyze the distribution of flights by airline.
  - Visualize flight patterns throughout the week.
  - Interact with maps for a geospatial understanding of destinations.
    
**2. Relationship with Weather Conditions and Congestion Dashboard:**

  - Examine the relationship between flight delays and weather conditions.
  - Analyze factors such as temperature, wind, and gusts in relation to delays.
  - Consider airport congestion and its impact on flight punctuality.

### Data Sources:
The project is based on three data sources obtained during a previous ETL project:

1. Detailed flight data, including information on airlines, schedules, statuses, and delays.
2. METAR weather reports corresponding to the same period, linked to each flight.
3. Flight statistics at Adolfo Suárez Madrid-Barajas Airport provided by EUROCONTROL.
   
### Usage Instructions:
**1. Power BI:**

  - Import the data into Power BI to explore the dashboards interactively.
  - Analyze destinations, airlines, days of the week, and relationships between delays and weather conditions.
     
**2. Code and ETL:**
  - Explore the source code to understand the ETL process and data source integration.
  - Ensure you have the necessary libraries to replicate the process in your environment.

## Dashboard Storytelling: Exploring Adolfo Suárez Madrid-Barajas Airport Flights
### Welcome and Temporal Filter
As we embark on this journey, our first stop is the temporal filter, located prominently at the top. A dynamic slider spanning from November 1, 2022, to October 31, 2023, sets the stage for our exploration through a year's worth of flight data.

### Airlines Insight: Top 10 Carriers
Direct your attention to the next feature — a filter showcasing the top 10 airlines with the highest flight frequencies. Use this to tailor your analysis to the carriers dominating the skies over Adolfo Suárez Madrid-Barajas Airport. Dive into the rich tapestry of airline diversity by engaging with the Top 10 Carriers filter. Click on any airline to not only spotlight its individual performance but also dynamically update the Top 6 Destinations filter, offering a nuanced view of the most frequented destinations by your selected carrier.

### Key Metrics at a Glance
On the left side, four informative labels catch your eye, presenting essential metrics:

- **Total Flights:** The overall count of flights during the selected period.
- **Number of Airlines:** A glimpse into the diversity of carriers operating from the airport.
- **Number of Destination Cities:** Explore the reach of flights by uncovering the number of cities served.
- **% Uninterrupted Flights:** Delve into the reliability of flights with the percentage of non-cancelled or diverted flights.
- 
### Dive into Popular Destinations
Explore the globe by narrowing down your focus using the filter displaying the six most visited destinations. But that's not all — click on a destination to illuminate the airlines responsible for connecting Adolfo Suárez Madrid-Barajas Airport to that specific location. The Top 10 Carriers filter dynamically adjusts, spotlighting the airlines facilitating the chosen route.

### Departure and Arrival Status Overview
Two engaging donut charts steal your attention, depicting the departure and arrival statuses. Observe the distribution of flights categorized as early, late, or on time. Experience the pulse of the airport with this interactive charts showcasing departure and arrival statuses. Click on a segment to filter and zoom in on specific performance metrics for a selected time frame.

### Temporal Trends: Daily Flight Count
Descend further to find a temporal graph, capturing the daily ebb and flow of flight activity. Witness trends and spikes, and consider how external factors or events might influence these patterns. Each click allows you to zoom into specific dates or periods, unveiling the story behind fluctuations in flight activity.

### Further Insights: Weekday Tree Map and Global Map
As we reach the culmination of our exploration, encounter a tree map showcasing flight distribution across the days of the week. Additionally, a world map lights up with destinations, creating a visual spectacle of global connectivity.Pinpoint busy days and quiet periods with a click. The global map, too, responds to your selections, illuminating the connectivity between Adolfo Suárez Madrid-Barajas Airport and destinations worldwide.

### Conclusion
This dynamic dashboard invites you to not only observe but actively engage with the data. Your clicks create ripples, revealing interconnected narratives within the bustling world of flights from Adolfo Suárez Madrid-Barajas Airport. Feel free to interact with the filters, charts, and maps to uncover hidden stories within the data. Bon voyage!
