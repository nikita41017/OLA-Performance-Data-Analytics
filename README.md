# OLA-Performance-Data-Analytics-Using-MS.EXCEL-SQL-POWER-BI

# PROJECT OVERVIEW

This project focuses on analyzing OLA ride data to uncover operational inefficiencies, improve performance, and enhance customer satisfaction. By leveraging SQL for data exploration and Power BI for visualization, the analysis provides actionable insights to support data-driven business decisions.

# Objectives
* Analyze booking trends, cancellation reasons, customer ratings, and revenue metrics.
* Identify patterns affecting operational performance and customer satisfaction.
* Provide visual insights through interactive Power BI dashboards.
* Recommend strategies to reduce cancellations and improve service efficiency.

# Dataset
The dataset includes OLA ride information such as booking status, trip details, customer ratings, and revenue data.

* SQL Dataset: link

# Business Problems and Solutions 

1. Retrieve all successful bookings:

select *
from bookings
where `Booking Status` = 'Successful';
select *
from bookings
where `Booking Status` = 'Successful';

# Findings
* Booking Trends: The majority of rides are completed, but a significant portion is canceled due to  driver unavailability and high wait times.
* Revenue Growth: Revenue peaks during weekends and festive seasons, highlighting opportunities for  targeted promotions.
* Customer Satisfaction: Cities with better driver availability and lower wait times show higher      average ratings.
* Peak Hours: Demand is highest during morning (8–10 AM) and evening (5–8 PM) commute hours.
* 
 # Conclusions
 
The analysis reveals that operational efficiency can be improved by:

* Reducing Cancellations: Addressing driver unavailability and reducing wait times.
* Dynamic Pricing: Implementing surge pricing during peak hours to balance supply and demand.
* nDriver Incentives: Rewarding top-performing drivers to boost service quality.
  
# Future Work

* Integrate real-time data to optimize ride dispatching.
* Analyze customer feedback for service improvement.
* Compare OLA’s performance with competitors to identify market gaps.

