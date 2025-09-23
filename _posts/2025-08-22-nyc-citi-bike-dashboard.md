---
layout: post
title: "Case Study: NYC Citi Bike Strategic Dashboard"
date: 2025-08-22
excerpt: "A data-driven analysis of over 30 million trip records to provide actionable recommendations for fleet management and service expansion."
image:
  path: assets/images/thumbnails/citi-bike-thumbnail.png
  alt: A dashboard showing Citi Bike usage data.
tags: [python, pandas, plotly, kepler.gl, streamlit]
github_link: https://github.com/fariyaasghar/nyc-citi-bike-dashboard
demo_link: https://nyc-citi-bike-dashboard.streamlit.app/
presentation_link: /assets/pdf/Fariya_Asghar_Portfolio_Deck.pdf # Path to the PDF
presentation_page: 39 # The slide number
---

### The Challenge

New York City's Citi Bike service experienced explosive growth in 2022, leading to significant logistical challenges. Customers frequently reported a lack of available bikes at popular stations, while other stations were often full, making bike returns impossible. I was tasked with analyzing the complete 2022 trip dataset to diagnose the root causes of these distribution issues and provide data-driven recommendations to the business strategy team.

### The Process

This project was executed in a multi-stage data analysis pipeline, moving from raw data to a polished, interactive final product. The key stages included **Data Sourcing & Enrichment** via the NOAA API, large-scale **Data Processing with Pandas**, and interactive **Visualization & Dashboard Development** using Plotly, Kepler.gl, and Streamlit.

### Key Insights & Visualizations

#### 1. Station Popularity is Highly Seasonal
The interactive stacked bar chart clearly shows that while some stations are popular year-round, the vast majority of trips occur during the warmer Summer and Fall months.

![Screenshot of the Stacked Bar Chart](/assets/images/stacked_bar_chart.png)

#### 2. Ridership is Directly Correlated with Temperature
The dual-axis line chart provides definitive proof of the seasonal effect, showing an undeniable positive correlation between daily trips and average temperature.

![Screenshot of the Line Chart](/assets/images/line_chart.png)

#### 3. The City's "Bike Highways" are Clearly Identifiable
By visualizing and filtering the top 1,000 routes, the geospatial map reveals the city's primary transportation corridors, highlighting immense traffic on major crosstown streets and over the bridges connecting to Brooklyn.

![Screenshot of the Kepler Map](/assets/images/kepler_map.png)

### Strategic Recommendations

Based on these insights, I provided three key, actionable recommendations:
1.  **Implement Dynamic, Season-Aware Rebalancing:** Focus logistical efforts on "all-weather" commuter hubs in the winter, and expand to the full top 20 list during the Summer and Fall peak.
2.  **Optimize Fleet Size Based on Seasonal Demand:** Scale back the active bike fleet by 40-50% in the coldest months to significantly reduce operational costs.
3.  **Develop a Dual Strategy for Commuter vs. Leisure Hotspots:** Treat A-to-B commuter "highways" differently from recreational round-trip hubs, focusing on rush-hour availability for one and high-volume capacity on weekends for the other.
