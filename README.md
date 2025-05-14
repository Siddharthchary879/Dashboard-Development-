# Dashboard-Development-

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : VADLA SIDDHARTHA CHARY

*INTERN ID* : CT12WUWQ

*DOMAIN* : Data Analytics

*DURATION* : 12 weeks

*MENTOR* : NEELA SANTOSH

##The Power BI dashboards provide a comprehensive analysis of US flight data, covering multiple aspects like flight volume, airline performance, delays, and airport efficiency. The dashboards are broken into four major sections:
1. Flight Summary Dashboard
•	Offers high-level KPIs (e.g., total flights, aircraft, carriers).
•	Identifies busiest months, days, and most used aircraft.
•	Helps in understanding overall flight traffic and aircraft utilization.
2. Airline Delay Dashboard
•	Analyzes airline performance based on delays.
•	Highlights worst-performing airlines (AA, WN).
•	Shows month-wise delay trends and delay causes by carrier.
3. Reason-wise Delay Dashboard
•	Breaks down flight delays into reasons: carrier, NAS, weather, late aircraft, security.
•	Shows which causes contribute most to delays.
•	Provides tail-number-specific delay insights.
4. Airport-wise Delay Dashboard
•	Analyzes which airports have the highest delays.
•	Highlights average delay times by origin and destination airports.
•	Helps identify bottleneck airports (e.g., ORD, EWR, ATL).
Key Findings
Category	Insight
Top Airline (by flights)	Southwest (WN) – 47% of total flights
Top Delay Causer (airline)	American Airlines (AA) – 15% of delays
Top Delay Reason	Carrier-related issues (50%+)
Most Delayed Airports	ORD (Chicago), EWR (Newark), ATL (Atlanta)
Most Flights in Month	July and May
Least Delays	January and October

STEP-BY-STEP GUIDE TO CREATING DASHBOARDS IN POWER BI
Step 1: Import Data
•	Open Power BI Desktop.
•	Click “Home > Get Data > Excel/CSV” and load your flight dataset.
•	Use Power Query Editor to clean data (remove nulls, change formats).
Step 2: Data Cleaning & Transformation
•	Format columns: date fields, distance as number, delay time as duration.
•	Rename columns for clarity.
•	Create calculated columns if needed (e.g., Flight Month, Flight Day, Total Delay).
Step 3: Create Relationships
•	If using multiple tables (e.g., Flights, Carriers, Airports), set relationships via:
o	Manage Relationships > Auto-detect
o	Use Primary Key – Foreign Key logic.
Step 4: Build Individual Dashboards
1. Flight Summary Dashboard
•	Cards: Total Flights, Unique Aircraft, Carriers, Cancelled Flights.
•	Bar Chart: Flights by Month.
•	Pie Chart: Top 5 Airlines by flight volume.
•	Line Chart: Flights by Weekday.
•	Donut Chart: Aircraft usage.
•	Area Chart: Aircraft Count by Distance.
2. Airline Delay Dashboard
•	Cards: Avg. Delay (Arrival & Departure), Total Delay minutes.
•	Line Chart: Delay per Month.
•	Pie Chart: Delay % by Airline.
•	Bar Chart: Total Delay by Carrier.
3. Reason-Wise Delay Dashboard
•	Pie Chart: Delay distribution by reason.
•	Bar/Line Chart: Delay by Tail Number.
•	Stacked Bar: Delay Types by Airline.
•	Line Chart: Monthly Delay %
4. Airport-Wise Delay Dashboard
•	Line/Bar Chart: Avg Delay by Origin & Destination Airport.
•	Stacked Bar: Delay by Reason per Airport.
•	Cards: Total Diverted Flights, No. of Airports.
Step 5: Add Slicers and Filters
•	Use slicers for:
o	Date range
o	Airline
o	Airport
o	Delay type
•	This improves interactivity and filtering for user analysis.
Step 6: Format and Design
•	Use a consistent color theme.
•	Use titles for each visual.
•	Apply data labels, legends, and tooltips.
•	Arrange visuals in logical flow (top-down or left-right).
Step 7: Publish and Share
•	Save your report.
•	You can create dashboards online, schedule data refresh, or share with others.
