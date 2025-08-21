Project Title: College-Bus-Usage-Monitor

Submitted by: Shrushti Sah 

Roll Number: 2312res628  

Course: Bsc in Computer Science and Data Analytics

Institute: IIT Patna  

🎯 Project Overview
The College Bus Usage Monitor is an end-to-end analytics project designed to solve common challenges in managing a campus transportation network. By centralizing data on student ridership, routes, and timing, this dashboard transforms raw data into a strategic tool for data-driven decision-making. The primary goal is to help the transportation department reduce operational costs, improve resource allocation, and increase student satisfaction.


✨ Dashboard Features
This dashboard is composed of several interactive visuals that allow for a deep dive into the data:

KPI Cards: High-level metrics providing an at-a-glance summary of performance, including:

Total Number of Routes

Total Student Trips (by Student ID count)

Average Time of Travel

Interactive Slicers: Dynamic filters for Date Range and Route, allowing users to drill down into specific periods or service lines.

Bus Occupancy Analysis (Donut Chart): Visualizes the distribution of student ridership across different buses, highlighting the most and least utilized vehicles.

Geospatial Map: Plots bus activity geographically to provide spatial context to the data. (Note: The map in the screenshot uses a generic base layer).

Route-Wise Usage (Bar Chart): Compares the popularity of different routes based on the number of student riders, identifying key transportation corridors.

Peak Time Routes (Bar Chart): Identifies the most frequent student travelers and the times they travel (Morning vs. Afternoon Rush).

Peak Travel Times (Area Chart): A time-series analysis showing the volume of students throughout the day, clearly indicating morning and afternoon peak hours for each route.


🛠️ Technical Stack
Visualization & BI: Microsoft Power BI

Data Transformation: Power Query Editor (for data cleaning, shaping, and ETL processes)

Data Modeling: DAX (Data Analysis Expressions) for creating calculated columns and measures.

Data Source: The dashboard is designed to work with CSV files, Excel spreadsheets, or a direct connection to a SQL database.


📊 Key Insights & Analysis
The dashboard reveals several critical insights into the transportation network:

Route Popularity is Uneven: The "City Center" route is by far the most frequented, while the "Express DC" route has significantly lower ridership. This suggests an opportunity to re-evaluate the frequency or size of buses allocated to the express route.

Identifiable Peak Hours: There are two distinct rush hours: a morning peak (approx. 9-10 AM) and an afternoon peak (approx. 4-5 PM). Schedules should be optimized to ensure maximum bus availability during these windows.

Asset Utilization Varies: Bus B-202 is the workhorse of the fleet, carrying over 25% of the students. In contrast, other buses have lower occupancy rates. This data can inform decisions about vehicle maintenance schedules and fleet management.

Targeted Service Monitoring: The dashboard can identify "power users" (students who travel most frequently), which can be useful for surveys or feedback initiatives.


🔮 Future Enhancements
Real-Time Data: Integrate with live GPS data from buses for real-time tracking and occupancy updates.

Cost Analysis: Incorporate financial data to analyze the cost-per-rider for each route.

Predictive Analytics: Implement a forecasting model to predict future demand based on historical trends, academic calendars, and special events.

Student Feedback: Add a module to integrate and analyze student feedback collected via surveys.
