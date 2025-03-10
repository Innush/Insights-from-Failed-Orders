# Gett Ride Matching Analysis 🚖

## Project Overview

Gett, previously known as GetTaxi, is an Israeli-developed technology platform solely focused on corporate Ground Transportation Management (GTM). Their application allows clients to order taxis, and drivers to accept rides (offers).

When a client requests a ride through the application, the matching system searches for the most relevant drivers and offers them the order. This project investigates key matching metrics for orders that did not complete successfully - specifically, instances where customers didn't end up getting a car.

## Research Questions

This analysis focuses on the following key questions:

1. **Failure Distribution Analysis** 📊  
   Build a distribution of orders according to reasons for failure: cancellations before and after driver assignment, and reasons for order rejection. Which category accounts for the highest number of orders?

2. **Hourly Failure Patterns** ⏰  
   Analyze the distribution of failed orders by hour of day. Are there trends where certain hours have abnormally high proportions of specific failure categories? Which hours show the highest failure rates and how might this be explained?

3. **Cancellation Time Analysis** ⏱️  
   Investigate the average time to cancellation (with and without driver assignment) by hour. Identify and remove any outliers in the data. What conclusions can be drawn from these patterns?

4. **ETA Distribution** 🕒  
   Examine the distribution of average Estimated Time of Arrival (ETA) by hour. How can the observed patterns be explained?

5. **Geospatial Analysis & Skills Development** 🗺️  
   Using H3 (hierarchical hexagonal geospatial indexing system) and Folium packages:
   - Calculate how many size-8 hexagons contain 80% of all orders from the original datasets
   - Visualize these hexagons on a map, with color intensity representing the number of failed orders in each area
   - This component represents a significant professional development opportunity, providing hands-on experience with advanced geospatial indexing and visualization techniques that are highly valuable in modern data analytics

## Methodology

The analysis employs various data visualization techniques to identify patterns and insights in the ride matching process. We focus specifically on unsuccessful orders to identify potential areas for improvement in the matching algorithm and overall user experience.

## Tools & Libraries 🛠️

- Python (pandas, numpy, matplotlib) 🐍
- H3 (Uber's hierarchical geospatial indexing system) 🔷
- Folium (for interactive map visualizations) 🌐
- Seaborn (for statistical visualizations) 📈

## Deliverables 📋

The project will deliver comprehensive visualizations and analyses for each research question, with explanations of observed patterns and potential business implications.
