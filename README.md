## Business Problem
Logistics efficiency is critical for delivery companies. This project analyzes shipment data to identify patterns in delivery performance, route usage, and operational efficiency.

## Key Questions
• When do shipments peak (time & day)?  
• Which regions dominate shipping activity?  
• How do different route types (FTL vs Carting) impact delivery efficiency?  
• How accurate are estimated routes compared to actual delivery performance?  

## Dataset
• Source: Kaggle (Delhivery logistics dataset, 2018)  
• Data includes: shipment routes, delivery time, distance, location, and transport type  

## Methodology
• Data cleaning and preprocessing using Python  
• Exploratory Data Analysis (EDA)  
• Visualization of shipment patterns and operational metrics  
• Basic clustering and regression for pattern analysis  

## Key Analysis
• Shipment volume analyzed across months and weekdays  
• Route type comparison between FTL (Full Truck Load) and Carting  
• Geographic distribution of shipments across regions  
• Comparison between actual vs estimated (OSRM) time and distance  

## Key Insights
• Shipment activity peaks significantly in September, indicating seasonal demand  
• Wednesdays have the highest shipment completion rate compared to other days  
• FTL (Full Truck Load) dominates shipment volume but tends to involve longer delivery times  
• Carting routes are more time-efficient for shorter distances  
• Certain regions (e.g., Haryana, Karnataka, Maharashtra) act as major logistics hubs  
• Significant variation between actual and estimated routes suggests real-world constraints such as traffic and route conditions  

## Machine Learning (Optional)
• Regression analysis showed limited predictive accuracy due to variability in delivery conditions  
• Clustering identified patterns in shipment distribution and regional activity  

## Recommendations
• Optimize logistics planning during peak periods (especially September) to handle high demand  
• Utilize Carting routes for short-distance deliveries to improve efficiency  
• Improve route planning systems to reduce the gap between estimated and actual delivery performance  
• Focus operational resources on high-volume regions to maximize efficiency  
• Monitor mid-week (Wednesday) shipment spikes for better workforce and fleet allocation  

## Tools & Technologies
• Python (Pandas, NumPy, Matplotlib)  
• Google Colab  
• Tableau  

Delhivery Data Readme
