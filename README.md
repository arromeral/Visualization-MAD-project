# Visualization-MAD-project
<p align="center">
  <img width="1000" height="300" src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/92d57008-3786-48a3-aa5d-2a64b90d1f03">
</p>

## Description & Contents
This repository contains a data visualization project created using Power BI, focusing on analyzing flights departures from Adolfo Suárez Madrid-Barajas Airport over the past year. The visualization consists of two interactive dashboards providing detailed insights into various aspects of flights, correlating flight data, METAR weather reports, and EUROCONTROL airport statistics.

###[**Key Features**](https://github.com/arromeral/Visualization-MAD-project/blob/main/power_bi/mad_flights.pdf):
**1. General Analysis Dashboard:**

  - Explore popular destinations.
  - Analyze the distribution of flights by airline.
  - Visualize flight patterns throughout the week.
  - Interact with maps for a geospatial understanding of destinations.
    
**2. Relationship with Weather Conditions and Congestion Dashboard:**

  - Examine the relationship between flight delays and weather conditions.
  - Analyze factors such as temperature, wind, and gusts in relation to delays.
  - Consider airport congestion and its impact on flight punctuality.

### [**Data Sources**](https://github.com/arromeral/Visualization-MAD-project/tree/main/data):
The project is based on three data sources obtained during a previous ETL project:

- Detailed flight data, including information on airlines, schedules, statuses, and delays.
- METAR weather reports corresponding to the same period, linked to each flight.
- Flight statistics at Adolfo Suárez Madrid-Barajas Airport provided by EUROCONTROL.
   
### Usage Instructions:
 1.[**Power BI**](https://github.com/arromeral/Visualization-MAD-project/blob/main/power_bi/mad_flights.pbix)

  - Import the data into Power BI to explore the dashboards interactively.
  - Analyze destinations, airlines, days of the week, and relationships between delays and weather conditions.
     
 2.[**Code & ETL**](https://github.com/arromeral/ETL-MAD-arromeral/tree/main)
  - Explore the source code to understand the ETL process and data source integration.
  - Ensure you have the necessary libraries to replicate the process in your environment.

## General Analysis Dashboard: Exploring Adolfo Suárez Madrid-Barajas Airport Flights
### Welcome and Temporal Filter
As we embark on this journey, our first stop is the temporal filter, located prominently at the top. A dynamic slider spanning from November 1, 2022, to October 31, 2023, sets the stage for our exploration through a year's worth of flight data.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/a0961b5d-014a-445a-95d6-3156f70169a4">
</p>

### Airlines Insight: Top 10 Carriers
Direct your attention to the next feature — a filter showcasing the top 10 airlines with the highest flight frequencies. Use this to tailor your analysis to the carriers dominating the skies over Adolfo Suárez Madrid-Barajas Airport. Dive into the rich tapestry of airline diversity by engaging with the Top 10 Carriers filter. Click on any airline to not only spotlight its individual performance but also dynamically update the Top 6 Destinations filter, offering a nuanced view of the most frequented destinations by your selected carrier.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/80c1ee9b-c03f-4526-a8d6-c3dd40824fc1">
</p>


### Key Metrics at a Glance
On the left side, four informative labels catch your eye, presenting essential metrics:

- **Total Flights:** The overall count of flights during the selected period.
- **Number of Airlines:** A glimpse into the diversity of carriers operating from the airport.
- **Number of Destination Cities:** Explore the reach of flights by uncovering the number of cities served.
- **% Uninterrupted Flights:** Delve into the reliability of flights with the percentage of non-cancelled or diverted flights.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/c2d960ce-406b-45c4-ae8c-3187a38107ea">
</p>

### Dive into Popular Destinations
Explore the globe by narrowing down your focus using the filter displaying the six most visited destinations. But that's not all — click on a destination to illuminate the airlines responsible for connecting Adolfo Suárez Madrid-Barajas Airport to that specific location. The Top 10 Carriers filter dynamically adjusts, spotlighting the airlines facilitating the chosen route.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/d77b5eb7-a27e-41a6-969a-f288d4e04e3d">
</p>

### Departure and Arrival Status Overview
Two engaging donut charts steal your attention, depicting the departure and arrival statuses. Observe the distribution of flights categorized as early, late, or on time. Experience the pulse of the airport with this interactive charts showcasing departure and arrival statuses. Click on a segment to filter and zoom in on specific performance metrics for a selected time frame.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/682c3c1a-edea-45e0-a482-58b8bd090b61">
</p>

### Temporal Trends: Daily Flight Count
Descend further to find a temporal graph, capturing the daily ebb and flow of flight activity. Witness trends and spikes, and consider how external factors or events might influence these patterns. Each click allows you to zoom into specific dates or periods, unveiling the story behind fluctuations in flight activity.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/da4c16c2-35a0-4466-85fa-ab1a20961ebb">
</p>


### Further Insights: Weekday Tree Map and Global Map
As we reach the culmination of our exploration, encounter a tree map showcasing flight distribution across the days of the week. Additionally, a world map lights up with destinations, creating a visual spectacle of global connectivity.Pinpoint busy days and quiet periods with a click. The global map, too, responds to your selections, illuminating the connectivity between Adolfo Suárez Madrid-Barajas Airport and destinations worldwide.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/31357fbf-0818-4443-9313-2f0582da94d8">
</p>

### Conclusion
This dynamic dashboard invites you to not only observe but actively engage with the data. Your clicks create ripples, revealing interconnected narratives within the bustling world of flights from Adolfo Suárez Madrid-Barajas Airport. Feel free to interact with the filters, charts, and maps to uncover hidden stories within the data. Bon voyage!

## Weather-Flight Dynamics Unleashed
### Welcome and Temporal Filter
Embark on a dynamic journey exploring the intricate relationship between meteorological conditions and flight performance. The adventure begins by setting the temporal scope with the slider, spanning from November 1, 2022, to October 31, 2023.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/096514ef-c5b1-4194-82d5-dbe96bf8b667">
</p>

### Weather Parameters: Temperature, Wind, and Gusts
Your exploration takes flight with interactive sliders to the left. Tweak the temperature, wind speed, and gust speed ranges to witness real-time adjustments in the heart of the dashboard. The charts and labels dynamically respond, immersing you in the ever-changing interplay of weather and flights.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/4201c577-73bf-4dcd-b4d2-fd2b1516de8e">
</p>

### Meteorological Conditions Filter
In the center stage, explore 15 meteorological conditions, each a portal to a unique facet of the weather-flight dynamic. Click on a condition, and watch as the donut chart and accompanying labels transform instantly, offering a personalized glimpse into how specific weather scenarios impact arrival statuses.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/2fdbae3e-5339-4d3e-954b-879e5cba174b">
</p>

### Weather Impact: Unveiling the Storm
As you interact, observe the profound influence of adverse weather conditions. High wind speeds and gusts emerge as significant players in the flight performance story. Click through the meteorological conditions to uncover the intricate dance between weather adversity and flight delays. The charts vividly portray the impact of challenging weather scenarios, providing insights into delays and disruptions. 
The central donut chart becomes a canvas of interactivity. Click on individual slices to isolate and examine specific arrival statuses. The labels alongside dynamically shift to reflect the percentage of flights facing delays exceeding 30 and 60 minutes. Immerse yourself in the live narrative, tailored to your chosen meteorological conditions.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/cc317b2c-eff9-49e4-a8c6-608a226b58f3">
</p>

### Daily Flight Count Trends
Gaze to the left, where the label unveils the total number of flights during the selected period. Interact with the temporal graph illustrating daily flight counts. Witness the ripple effect of your interactions across the entire dashboard as you focus on specific temperature, wind, and gust ranges.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/905c43f2-f11a-47c8-9c83-54af77a33b7a">
</p>

### Punctuality Insights: Eurocontrol Data
Descend to the bottom, where the temporal graph unveils the percentage of daily flights departing punctually. Click on meteorological conditions in the bar chart to unveil the correlation between specific weather scenarios and departure punctuality. Every click transforms the narrative, empowering you to tailor the story to your unique perspective.
<p align="center">
  <img src="https://github.com/arromeral/Visualization-MAD-project/assets/138980560/af01b1a2-d1e7-4798-b737-f4cda80f8c21">
</p>

### Interactive Mastery
This dashboard is your canvas. Every adjustment to sliders, every click on meteorological conditions, crafts a bespoke narrative. Become the master of the story, unraveling the mysteries of weather-flight dynamics with every interaction.

### Conclusion
As you navigate this immersive experience, remember that every interaction tells a story. Immerse yourself, experiment, and unveil the secrets of meteorological insights and flight status revelations. Your journey, your narrative—unfold it with every click!
