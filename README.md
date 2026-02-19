# Ride-booking-analytics-dashboard
Power BI dashboard analyzing ride booking demand, operational efficiency, and cancellation behavior.

# Ride Booking Analytics Dashboard (Power BI)

## Project Overview

This project analyzes 2024 ride-booking data to uncover demand trends, operational efficiency, and cancellation behavior.

The dashboard is structured into three key pages:

1️⃣ Executive Overview
- Total bookings, revenue, and completion rate
- Monthly performance trends

2️⃣ Time & Demand Patterns
- Hourly booking demand
- Weekday vs weekend behavior
- Completion rate variations by hour

3️⃣ Operational Bottlenecks & Root Causes
- Cancellation rate analysis
- Customer vs driver cancellation breakdown
- Impact of vehicle arrival time (VTAT) on ride cancellations

---

## Tools and Technologies  

- Power BI Desktop  
- Power Query (Data Cleaning & Transformation)  
- DAX (KPI Calculations & Measures)  
- Data Modeling (Star Schema)  

---

## Methods  

### 1️⃣ Data Cleaning
- Handled missing values appropriately  
- Converted data types  
- Standardized categorical values  
- Created time-based attributes (Hour, Weekday, Weekend flag)

### 2️⃣ Data Modeling
- Designed a structured model with a dedicated Date Table  
- Established one-to-many relationships  

### 3️⃣ KPI Engineering (DAX)
Created measures for:
- Total Bookings  
- Completion Rate  
- Cancellation Rate  
- Total Revenue  
- Average Booking Value  
- Avg VTAT  

### 4️⃣ Analytical Approach
- Time-based demand pattern analysis  
- Operational efficiency measurement  
- Root-cause investigation of cancellations  
- Correlation analysis between VTAT and cancellation rates  

---

## Key Insights  

- Peak demand occurs during morning and evening commute hours  
- Completion rate slightly declines during high-demand periods  
- Driver-side cancellations contribute significantly to overall ride failures  
- Higher vehicle arrival time (VTAT) correlates with increased cancellation rates  
- Weekday demand exceeds weekend demand  

---

## Dashboard 

The dashboard consists of three interactive pages:

### 1️⃣ Executive Overview
- Business KPIs  
- Monthly performance trends  

### 2️⃣ Time & Demand Patterns
- Hourly demand trends  
- Completion rate by hour  
- Weekday vs weekend comparison  

### 3️⃣ Operational Bottlenecks & Root Causes
- Cancellation rate analysis  
- Customer vs driver cancellation breakdown  
- Impact of VTAT on cancellations  

📎 The exported dashboard PDF is included in this repository.

---

## How to Run This Project?  

1. Download the `.pbix` file from this repository  
2. Open using **Power BI Desktop**  
3. Use the Vehicle Type slicer to interact with the dashboard  
4. Navigate across pages for complete analysis  

Alternatively, view the exported PDF version for a static overview.

---

## Results & Conclusion  

This project demonstrates how ride-booking data can be transformed into meaningful operational insights.  

The dashboard identifies peak demand windows, operational inefficiencies, and root causes of cancellations, enabling data-driven decision-making for improving platform performance.

---

## Author & Contact  

**Dhruv Prasad**  

Email: dhruvprasad2005@gmail.com  
LinkedIn: www.linkedin.com/in/dhruvprasad05

