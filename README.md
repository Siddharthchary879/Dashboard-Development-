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

## Output

![Image](https://github.com/user-attachments/assets/4b5986f2-f11d-4253-8c22-fd85d2b5ac36)

This final dashboard focuses on which airports face the most delays, both at origin and destination ends.
Key Metrics
Metric	Description
303 Origin Airports	Total departure airports.
304 Destination Airports	Total arrival airports.
7754 Flights Diverted	Flights that didn’t land at their original destination.

Visualizations
1. Delays by Origin Airport (Line Chart)
•	Airports like DFW (Dallas), DEN (Denver), ATL (Atlanta) show high delays.
•	NAS and Carrier-related delays dominate.
2. Delays by Destination Airport
•	MSP (Minneapolis) and ORD (Chicago O’Hare) experience significant arrival delays.
3. Average Delay by Origin Airport (Bar Chart)
•	ORD and SFO have high average delay times for departures.
4. Average Delay by Destination Airport
•	EWR (Newark) and ORD are most delayed for arrivals.
•	These are major hubs, so delays could be due to heavy traffic or congestion.
5. Reason-wise Delay by Origin Airport (Stacked Bar Chart)
•	Helps compare how much delay each reason (Carrier, NAS, Weather, Security) contributes at each airport.
•	ATL, ORD, DTW have noticeable delays across multiple categories.

![Image](https://github.com/user-attachments/assets/b5083c2c-7c74-44c2-a634-f069cb0fc758)

This dashboard analyzes what causes flight delays: weather, airline issues, security, etc.
Key Metrics
Metric	Meaning
6005 Security Delays	Delays due to security checks/issues.
658K NAS Delays	National Aviation System delays (air traffic control, etc).
99K Weather Delays	Bad weather–caused delays.
656K Carrier Delays	Delays caused by the airline’s internal issues.
Avg Arrival Delay: 42.20 mins	Slightly lower than total average.
Avg Departure Delay: 43.19 mins	Consistent with other reports.
Late Aircraft Delay: 25.30 mins	Caused when previous flight arrived late.

Visualizations
1. Delay by Reason (Pie Chart)
•	Shows share of each delay reason:
o	Carrier Delay is the highest: 50.48%
o	Followed by NAS Delay: 39.54%
o	Weather, Security, and Late Aircraft are smaller contributors.
2. Late Aircraft Delay by Tail Number (Bar & Line Chart)
•	Specific planes (like N265SW, N320SW) often cause delays.
•	Helps airlines identify problematic aircraft.
3. Delayed Flights by Month (%) (Line Chart)
•	Delay rates vary by month.
•	August (Month 8) has highest percentage of delayed flights.
•	January (Month 1) has the lowest—possibly due to fewer flights.
4. Carrier-wise Delay Type (Bar Chart)
•	WN and AA again appear as major sources of all delay types—arrival, departure, NAS, etc.

![Image](https://github.com/user-attachments/assets/152f5083-cf56-449c-a1b1-fcd7444cb32c)

This dashboard focuses on delays caused by each airline (carrier) and how they compare over time.
Key Metrics
Metric	Meaning
20 Carriers	20 different airlines in the dataset.
Avg Departure Delay: 56.41 mins	Average delay before takeoff.
Avg Arrival Delay: 58.41 mins	Average delay on arrival.
Total Arrival Delay: 38M mins	All airlines combined.
Total Departure Delay: 37.03M mins	Total delay time before takeoff.

Visualizations
1. Monthly Carrier Delay (Line Chart)
•	Shows average carrier delay for each month.
•	February and December have the highest delays—possibly due to bad weather or holiday congestion.
•	October and November have lower delays.
2. Carrier Delay % (Pie Chart)
•	Distribution of delays among carriers.
•	AA (American Airlines) causes the most delays: 15.81%.
•	Other top contributors: WN, YV, UA.
3. Total Delay by Carrier (Bar Graph)
•	Which airline has the highest total delay time?
•	WN (Southwest) and AA (American) are responsible for the most delay minutes.
4. Aircraft Count vs. Delay (Line Graph)
•	Compares number of aircraft to average delay.
•	Most aircraft have minimal delays.
•	Only a few planes are extremely delayed—these could be outliers or indicate maintenance issues.

![Image](https://github.com/user-attachments/assets/e3a306c9-1da6-4e43-aaa4-4c914f584f82)

This dashboard gives an overall picture of flight data, including aircraft, carriers, cancellations, and flight performance.
Key Metrics (KPI Cards at the Top)
Metric	Description
1.94M Flights	Total number of flights analyzed in the dataset.
7499 Unique Flights	Total different flight numbers (flight routes).
5367 Aircraft	Unique aircraft (identified by tail numbers).
20 Carriers	Total number of airline companies involved.
633 Flights Cancelled	Number of flights that were cancelled.
1.46% Delayed Flights	The percentage of flights that experienced delays.
100% of Delayed Flights	Ensures full data coverage for delayed flights.

Visualizations
1. Flight Count by Month (Bar Chart)
•	Shows how many flights occurred each month.
•	Months 5 (May) and 7 (July) have the highest flight volumes, possibly due to summer travel.
•	Helps in understanding seasonal travel trends.
2. Top 5 Carriers by Flight Count (Pie Chart)
•	Shows the percentage share of top 5 airlines.
•	WN (Southwest Airlines) leads with 47.15% of total flights.
•	Other major carriers: MQ, OO, EV.
3. Flight Count by Distance (Bar Chart)
•	Groups flights based on the distance traveled.
•	Most flights are short to medium range (under 2000 miles).
•	Long-haul flights are fewer.
4. Flight Count by Day of the Week (Line Chart)
•	Shows weekly flight distribution.
•	Friday (Day 5) is the busiest day.
•	Monday (Day 2) has the least number of flights.
5. Aircraft by Flight Number (Donut Chart)
•	Shows which aircraft fly which flight numbers.
•	Some aircraft (like N5433, N5737) are used for multiple flights, indicating operational efficiency.
6. Aircraft Count by Distance (Area Chart)
•	Maps number of aircraft to the distance ranges they cover.
•	Many aircraft fly in the 4200–4400 miles range, suggesting optimal aircraft assignment.
7. Taxi In/Out Time by Tail Number (Bar Chart)
•	Shows how long specific aircraft spend taxiing on runways.
•	High taxi times for planes like N605, N942, could indicate airport congestion or operational delays.

Overall Analysis: Summary
Focus Area	Key Insight
Most Flights	May and July (Month 5 & 7)
Busy Day	Friday (Day 5)
Top Airline (by volume)	WN (Southwest)
Top Delay Contributor (Airline)	AA (American Airlines)
Top Delay Reason	Carrier-related (airline issues)
Top Delayed Airports	ORD, ATL, DFW, EWR
Worst Delay Month	August (Month 8)
Most Common Delay Type	NAS and Carrier delays

