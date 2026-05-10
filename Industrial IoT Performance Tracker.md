### Industrial IoT Performance Tracker

#### A Power BI Analytics Dashboard for Global Factory Monitoring



##### Project Overview

This project transforms raw telemetry data from 180,000+ IoT sensors into a functional business dashboard. The goal was to monitor the health and temperature of 36 unique industrial devices across four global manufacturing hubs: Berlin, Shenzhen, Tokyo, and Osaka.



##### Technical Stack

* Tool-Purpose
* Power BI- Data Visualization \& Dashboarding
* Power Query (M)- "JSON Flattening, Data Cleaning, \& Unix Conversion"
* DAX- Time-Series Analytics \& Chronological Sorting Logic



##### Key Features \& Insights



* Global Fleet Overview: Real-time tracking of 36 devices with "Distinct Count" logic to ensure data accuracy.
* Automated Health Status: A conditional logic system that flags devices as "Unhealthy" if temperatures exceed thresholds.
* Time-Series Analysis: A continuous timeline tracking temperature spikes across nine different machine types (CNCs, Furnaces, etc.).
* Actionable Maintenance Table: A specific "High Priority" list that filters only unhealthy devices for immediate technician intervention.



##### The Technical Challenge



* JSON Flattening: Handled deeply nested JSON structures to extract deviceType, factory, and telemetry data.
* Timestamp Logic: Converted raw Unix Epoch timestamps into human-readable Date/Time formats for accurate historical analysis.
* Chronological Sorting: Developed a custom DAX Sort Key (YEAR \* 100 + MONTH) to force alphabetical text month names into their correct calendar order.



##### Final Dashboard Preview

![Industrial IoT Dashboard](<Power BI project-1.png>)


Note on Data: This dashboard monitors a massive signal volume of 160.6K records, maintaining a 99.9% health rating across the fleet while isolating the critical 0.06% of failure points.

