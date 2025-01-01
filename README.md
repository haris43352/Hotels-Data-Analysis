**Hotel Data Analysis**

**Overview**

This project analyzes hotel data from major cities in India, including Mumbai, Hyderabad, Bangalore, and Delhi. The data is sourced from multiple tables: facts_aggregated_booking, facts_booking, dim_rooms, dim_hotels, and a dimension table dim_date. The goal was to clean, transform, and visualize the data to uncover insights related to revenue, occupancy, ratings, and other key metrics. The insights are presented in a dashboard to help stakeholders make data-driven decisions.

**Steps Performed in the Analysis**

**Data Cleaning and Transformation**

Cleaned and preprocessed the data, removing inconsistencies and aligning data types.
Added a calculated column Week in the dim_date table using the WEEKNUM formula.
Created a calculated column Day Type to differentiate weekdays and weekends.
Applied transformations to link the data across tables for a unified analysis.

** Key Metrics and Measures**

Developed various measures to analyze performance, including:

Revenue
Realization %
Occupancy %
Cancellation %
Total Bookings and Successful Bookings
Average Daily Rate (ADR)
DSRN (Daily Sold Room Nights)
DURN (Daily Utilized Room Nights)
RevPAR (Revenue Per Available Room)
Total Capacity
Detailed information about these metrics is available in the Metric List file.

**Dashboard Components**

**1. Revenue by Category**

Donut Chart: Showcased the revenue distribution:
61% of the revenue comes from the "Business" category.
39% comes from the "Luxury" category.

**2. Key Metrics Overview**

Listed metrics like Revenue, RevPAR, DSRN, Occupancy %, Realization %, and ADR with week-to-week percentage changes to monitor trends and performance.

**3. Realization % and ADR by Booking Platform**

Bar and Line Chart:
Realization % is represented by bars.
ADR is depicted using a blue line.
This chart highlights platform-wise performance and suggests strategies for improving bookings via targeted offers like a 5% discount.

**4. Trend Analysis by Week**

Line Chart: Tracks weekly trends in ADR, Occupancy %, and RevPAR across all properties.
Observed a consistent ADR throughout weekdays and weekends, with minimal price variation.

**5. City and Property-Level Analysis**

Detailed Table: Showed key metrics such as city, property name, property ID, revenue, and ratings.
Identified four hotels with ratings below 3:
Two in Mumbai.
One in Hyderabad.
One in Bangalore.
Despite low ratings, these hotels generate decent revenue, indicating possible issues like service quality or unmet customer expectations.

**Key Insights and Recommendations**

**1. Pricing Strategies**

The small price difference between weekdays and weekends suggests an opportunity to optimize pricing strategies. Implement dynamic pricing to maximize revenue during high-demand periods.

**2. Focus on Low-Rating Hotels**

Investigate the four low-rating hotels to identify underlying issues (e.g., ambiance, staff behavior, or service quality).
Ensure promises made to guests are fulfilled to improve satisfaction and ratings.

**3. Increase Revenue through Offers**

Use targeted marketing strategies on booking platforms. For example, offer a 5% discount on direct bookings to attract more customers and increase realization %.

**4. Enhance Customer Experience**

Focus on providing a better user experience, especially in hotels with lower ratings, to align performance with guest expectations.

**5. Weekday and Weekend Pricing**

Address the negligible price variation between weekdays and weekends. Create strategies to incentivize weekday bookings and capitalize on weekend demand.
Tools and Technologies Used
Power BI: For creating the interactive dashboard and visualizing key insights.
SQL: To query and aggregate data for analysis.
Python: For data cleaning and transformation.
Excel: For managing raw data and performing preliminary checks.

**How to Use the Dashboard**

Open the Power BI file to access the dashboard.
Use filters (by city or room) to explore specific insights.
Analyze trends and metrics using the visualizations to understand key areas for improvement.
Refer to the recommendations section to implement actionable strategies based on the findings.
