# OLA_Ride_Cancelation_Analysis
<h2>What is the Project About?</h2>
<p>This project analyzes ride cancellation patterns in Ola to understand the key reasons behind cancellations and their impact on customer experience. The Goal is to :</p>
<li>Identify cancellation trends and patterns.</li>
<li>Find root causes behind failed rides.</li>
<li>Predict cancellations using machine learning.</li>
<li>Deliver insights using SQL views and Power BI dashboards.</li>

<h2>Why This Project?</h2>
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
<h2>Dataset Details</h2>
<p>The dataset includes the following key attributes:</p>

<li>Ride Details: Ride ID, Customer ID, Driver ID, Pickup & Drop Locations.</li>
<li>Cancellation Information: Reason for Cancellation, Who Canceled (Driver/Customer).</li>
<li>Booking Details: Time of Booking, Estimated vs. Actual Pickup Time.</li>
<li>Customer & Driver Metrics: Customer Ride History, Driver Cancellation Rate.</li>

<h2>How Was the Project Executed?</h2>
<h3>1. Data Understanding & Cleaning</h3>
<li>Data from ride bookings was cleaned using Python (Pandas)</li>
<li>Null values, redundant columns, and irrelevant fields like Unnamed were removed</li>
<li>Columns such as Only_Date, Time_Slot, Day_Name, Hour, and IS_WEEKEND were created for deeper analysis</li>
<li>Refer: 1_Understanding_Cleaning.ipynb</li>

<h3>2. Exploratory Data Analysis (EDA)</h3>
<li>Visualized booking status by time, day, vehicle, and customer behavior</li>
<li>Found patterns around when, where, and why cancellations occurred</li>
<li>Refer: 2_EDA.ipynb</li>

<h3>3. Machine Learning Model</h3>
<li>Target: Is_Cancelled (Success = 0, Canceled = 1)</li>
<li>Features: Vehicle_Type, Pickup_Location, Day_Name, Time_Slot, Booking_Value, etc</li>
<li>Used Logistic Regression to predict likely cancellations</li>
<li>Achieved valuable classification performance.</li>
<li>Outcome: Enables the company to preemptively flag risky bookings</li>

<h3>4. SQL Analysis</h3>
<li>Used SQL to answer business questions and create views:</li>
<li>Top vehicle types by distance</li>
<li>Cancellations by reason and source</li>
<li>High-value customers</li>
<li>Average ratings by vehicle type</li>
<li>Total revenue lost</li>
<li>Refer: Sql_BI_questions_ans.docx</li>

<h3>5. Power BI Dashboarding</h3>
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

<h3>6. Key Insights (Findings)</h3>
<p>
<h4>📉 Cancellations:</h4>
<li>38% of total rides were cancelled</li>
<li>Top reasons:</li>
  <li>> Driver unavailability</li>
  <li>> Location issues</li>
  <li>> Customers changing plans</li>
<li>Most cancellations occur during Morning & Night on weekdays (esp. Monday–Tuesday)</li>

<h4>🧑‍🤝‍🧑 Repeat Cancellers:</h4>
<li>372 customers cancelled rides multiple times</li>
<li>Drivers also canceled for these users due to health/safety concerns</li>
<li>Suggests behavior-based filtering is needed</li>

<h4>📍 Location Hotspots:</h4>
<li>Langford Town & Hosur Road had the highest cancellation rates as both pickup and drop locations</li>
<li>Targeted operations and driver incentives needed in these zones</li>

<h4>📈 Revenue & Ratings:</h4>
<li>Cancelled rides had lower average booking value</li>
<li>Lower driver/customer ratings are correlated with cancellations</li>
<li>Ratings can be used as early warning indicators </li>
</p>

<h3>7. Technologies Used</h3>
<li>Python (Pandas, Matplotlib) : Understanding the data, data cleaning, standarization, Exploratory data analysis and visuals.</li>
<li>SQL: Solving Business questions and created views.</li>
<li>Power BI: Interactive dashboards and in-depth visualizations.</li>
<li>Jupyter Notebook, MySQL Workbench</li>

<h3>8. Final Outcome</h3>
<li>✅ Delivered a complete Data Analytics + Machine Learning project</li>
<li>✅ Supported by SQL views, Power BI dashboards, and Python-based modeling</li>
<li>✅ Identified high-impact areas for operational improvement and revenue protection</li>

<h3>9. Conclusion</h3>
<p>This project provided a 360-degree view of ride cancellation behavior on a ride-hailing platform like Ola. Through a combination of Python for data cleaning and analysis, SQL for business logic, machine learning for prediction, and Power BI for visualization, we uncovered critical factors contributing to cancellations. We found that over 38% of rides were cancelled — primarily due to driver-related issues, location bottlenecks like Langford Town and Hosur Road, and peak-time booking failures during morning and night slots. Repeat cancellers and poor rating patterns further added to reliability risks.

By building a cancellation prediction model, we enabled the possibility of proactively identifying risky bookings before they fail. The Power BI dashboards made these insights accessible to non-technical stakeholders for real-time decision-making.

This project demonstrates how data can be used to drive actionable strategies for improving customer experience, optimizing driver allocation, and ultimately minimizing cancellation losses.</p>

<h3>10. Contact</h3>
<p>For queries, email sonawaneraj128@gmail.com or connect on LinkedIn [www.linkedin.com/in/raj-sonawane96659].</p>
