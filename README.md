# Hospitality-Domain-Dashboard
## Overview
This project focuses on building an interactive and insightful dashboard for the hospitality domain using Power BI. The dashboard provides actionable insights into key metrics such as occupancy rates, revenue per available room (RevPAR), and booking trends, enabling stakeholders to make informed decisions.
## Key Features
1. Integration of data from five key tables:
     * dim_date: Date dimensions for temporal analysis.
     * dim_hotels: Hotel-related details like location and category.
     * dim_rooms: Room-related details including type and capacity.
     * fact_bookings: Detailed booking records.
     * fact_aggregated_bookings: Pre-aggregated booking metrics for efficiency.
2. Custom measures for advanced analytics (e.g., occupancy rate, revenue).
3. Visualizations such as:
     * Bar charts for booking platform trends.
     * Line charts for revenue,Average daily Revenue,Revenue Per Available Room, occupancy rates over time.
     * Pie chart for hotel category.
     * Tables for detailed trends.

## Project Structure 

├── Hospitality Domain                                # Contains CSV files 
 
├── hospitality domain.pbix                           # Power BI dashboard file  

└── README.md                                         #  Project README file 


## Tools and Technologies
   * Power BI: For data visualization and dashboard creation.
   * Data Modeling: Star schema with dimension and fact tables.

## Setup Instructions
* Data Preparation:
   * Ensure the five tables (dim_date, dim_hotels, dim_rooms, fact_bookings, fact_aggregated_bookings) are loaded into a database or file format compatible with Power BI.
   * Clean and preprocess data as required.
* Power BI Configuration:
  * Import the data into Power BI.
  * Establish relationships between tables (star schema).
* Dashboard Development:
  * Create visualizations for key metrics.
  * Add custom measures using DAX (Data Analysis Expressions) for advanced analytics.
* Publishing and Sharing:
  * Publish the dashboard to Power BI Service.
    
  [dashboard](https://app.powerbi.com/links/6aV9HpnVWV?ctid=a9edca2b-3c0e-4fc7-a955-c4f451aed5cd&pbi_source=linkShare)

## Dashboard 
![Hospitality Dashboard1](https://github.com/user-attachments/assets/a6b3b5ff-5a6c-4840-8498-e52a6095f0d0)
![Hospitality Dashboard2](https://github.com/user-attachments/assets/564493c4-258b-4585-85a0-b176927f02b6)


 
