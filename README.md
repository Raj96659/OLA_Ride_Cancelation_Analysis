# OLA_Ride_Cancelation_Analysis
<h3>What is the Project About?</h3>
<p>This project analyzes ride cancellation patterns in Ola to understand the key reasons behind cancellations and their impact on customer experience. The Goal is to :</p>
<li>Identify cancellation trends and patterns.</li>
<li>Find root causes behind failed rides.</li>
<li>Predict cancellations using machine learning.</li>
<li>Deliver insights using SQL views and Power BI dashboards.</li>

<h3>Why This Project?</h3>
<p>Cancellations not only frustrate customers but also result in:</p>
<li>Revenue loss</li>
<li>Lower customer satisfaction</li>
<li>Operational inefficiency</li>
<br>
<p>Understanding "why and when" rides are cancelled allows the business to:</p>
<li>Improve driver allocation</li>
<li>Reduce avoidable cancellations</li>
<li>Increase ride completion rates</li>
<br>
<h3>Dataset Details</h3>
<p>The dataset includes the following key attributes:</p>

<li>Ride Details: Ride ID, Customer ID, Driver ID, Pickup & Drop Locations.</li>
<li>Cancellation Information: Reason for Cancellation, Who Canceled (Driver/Customer).</li>
<li>Booking Details: Time of Booking, Estimated vs. Actual Pickup Time.</li>
<li>Customer & Driver Metrics: Customer Ride History, Driver Cancellation Rate.</li>

<h3>How Was the Project Executed?</h3>
<h4>1. Data Understanding & Cleaning</h4>
<li>Data from ride bookings was cleaned using Python (Pandas)</li>
<li>Null values, redundant columns, and irrelevant fields like Unnamed were removed</li>
<li>Columns such as Only_Date, Time_Slot, Day_Name, Hour, and IS_WEEKEND were created for deeper analysis</li>
<li>Refer: 1_Understanding_Cleaning.ipynb</li>

<h4>2. Exploratory Data Analysis (EDA)</h4>
<li>Visualized booking status by time, day, vehicle, and customer behavior</li>
<li>Found patterns around when, where, and why cancellations occurred</li>
<li>Refer: 2_EDA.ipynb</li>

<h4>3. Machine Learning Model</h4>
<li>Target: Is_Cancelled (Success = 0, Canceled = 1)</li>
<li>Features: Vehicle_Type, Pickup_Location, Day_Name, Time_Slot, Booking_Value, etc</li>
<li>Used Logistic Regression to predict likely cancellations</li>
<li>Achieved valuable classification performance.</li>
<li>Outcome: Enables the company to preemptively flag risky bookings</li>

<h4>4. SQL Analysis</h4>
<li>Used SQL to answer business questions and create views:</li>
<li>Top vehicle types by distance</li>
<li>Cancellations by reason and source</li>
<li>High-value customers</li>
<li>Average ratings by vehicle type</li>
<li>Total revenue lost</li>
<li>Refer: Sql_BI_questions_ans.docx</li>

<h4>5. Power BI Dashboarding</h4>
<li>Created 10 key dashboards:</li>
<li>Ride Volume Over Time</li>
<li>Booking Status Breakdown</li>
<li>Top 5 Vehicle Types by Ride Distance</li>
<li>Average Customer Ratings per Vehicle</li>
<li>Cancellation Reasons</li>
<li>Revenue by Payment Method</li>
<li>Top Customers by Booking Value</li>
<li>Distance Trends by Day</li>
<li>Driver Ratings Distribution</li>
<li>Customer vs Driver Rating Comparison</li>

<h4>6. Key Insights (Findings)</h4>
<p>
📉 Cancellations:
38% of total rides were cancelled
Top reasons:
  > Driver unavailability
  > Location issues
  > Customers changing plans
Most cancellations occur during Morning & Night on weekdays (esp. Monday–Tuesday)

🧑‍🤝‍🧑 Repeat Cancellers:
372 customers cancelled rides multiple times
Drivers also canceled for these users due to health/safety concerns
Suggests behavior-based filtering is needed

📍 Location Hotspots:
Langford Town & Hosur Road had the highest cancellation rates as both pickup and drop locations
Targeted operations and driver incentives needed in these zones

📈 Revenue & Ratings:
Cancelled rides had lower average booking value
Lower driver/customer ratings are correlated with cancellations
Ratings can be used as early warning indicators  
</p>

<h3>Technologies Used</h3>
<li>SQL: Data extraction, cleaning, and transformation.</li>
<li>Excel: Exploratory data analysis (EDA) and initial visualization.</li>
<li>Power BI: Interactive dashboards and in-depth visualizations.</li>

<h3>Conclusion</h3>
<p>This analysis provides actionable insights into Ola’s ride cancellation patterns. By addressing key issues such as driver availability, pricing concerns, and long wait times, Ola can enhance customer satisfaction and reduce cancellation rates.</p>

<h3>Contact</h3>
<p>For queries, email sonawaneraj128@gmail.com or connect on LinkedIn [www.linkedin.com/in/raj-sonawane96659].</p>
