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
