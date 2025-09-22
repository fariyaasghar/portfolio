---
layout: post
title: "Case Study: Strategic Analysis of the Amsterdam Airbnb Market"
date: 2025-06-22
excerpt: "An end-to-end data science workflow using Python and Tableau to analyze the Amsterdam Airbnb market, from data wrangling to predictive modeling and strategic recommendation."
image:
  path: assets/images/thumbnails/airbnb-thumbnail.png
  alt: A map of Amsterdam showing Airbnb **Value Zones++.
tags: [Python, Tableau, Scikit-learn, GeoPandas, Machine Learning, Strategy]
github_link: https://github.com/fariyaasghar/Airbnb-Amsterdam-Market-Analysis
demo_link: https://public.tableau.com/views/FinalProject_17505974440610/Story1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
presentation_link: /assets/pdf/Fariya_Asghar_Portfolio_Deck.pdf # Path to the PDF
presentation_page: 29 # The slide number
---

### The Problem & Objective
In Amsterdam's dense and competitive Airbnb market, what are the true drivers of profitability? My objective was to move beyond surface-level metrics to identify the key factors that determine listing price, segment the market into distinct performance-based personas, and develop a strategic framework to guide investment decisions for new hosts.

**My Role:** I was the sole Data Analyst responsible for the entire project lifecycle, including data cleaning, feature engineering, statistical modeling, and creating the final interactive visualizations and strategic recommendations.  
**Duration:** 8 Weeks  
**Tools:** Python (Pandas, Scikit-learn, GeoPandas), Tableau

---

### The Process: From Myths to Models

My analysis began by testing a common assumption: that the best, most experienced hosts can command a higher price. The data revealed a surprising and counter-intuitive insight.

<!-- ACTION: Place your "Host Quality vs Price" dashboard screenshot in /assets/images/ and name it airbnb-quality-price.png -->
![A dashboard showing that high-quality hosts have a lower median price](/assets/images/airbnb-quality-price.png)
*Above: The data showed that "High-Quality Hosts" have a lower median price, proving that success in this market is likely about offering superior value to drive volume.*

#### Uncovering the True Drivers of Price
If quality wasn't the main driver, what was? I built a **multiple regression model** which confirmed three fundamental pillars of pricing: **Location**, **Room Type**, and **Size**. Together, these tangible assets were able to explain 53% of the variance in listing price.

#### Segmenting the Market with Machine Learning
To understand how listings compete, I used an unsupervised machine learning algorithm (**K-Means clustering**) to segment the market. The algorithm automatically identified three distinct business personas:
1.  **Premium & Large-Format:** High-price, high-margin listings.
2.  **High-Turnover Value Leaders:** Competitively-priced listings with near-constant occupancy.
3.  **Established Mid-Market:** Older listings with moderate performance.

---

### The Discovery: Two Viable Paths to Profitability

The most powerful insight came from analyzing the performance of these three segments over time. It revealed a classic business trade-off between sales volume and profit margin.

<!-- ACTION: Place your "Price vs. Volume" dashboard screenshot in /assets/images/ and name it airbnb-price-volume.png -->
![A dashboard showing the price vs. volume trade-off between market segments](/assets/images/airbnb-price-volume.png)
*Above: While the "High-Turnover" cluster maintains the highest occupancy, the "Premium" cluster generates the highest average annual revenue, revealing two distinct, successful strategies in the market.*

### Final Recommendations & Project Links

My final analysis provides a clear strategic framework for any potential investor, delivered in a fully interactive **Tableau Storyboard**.

<!-- ACTION: Place your final "Executive Summary" dashboard screenshot in /assets/images/ -->
![Screenshot of the final interactive Tableau Storyboard for the Airbnb analysis](/assets/images/airbnb-dashboard.png)

#### Key Recommendations:
A successful investment requires choosing a clear strategy and matching it to the right location and property type.
- **Path 1 (High-Volume):** Target smaller properties in "Value Zone" neighborhoods like Westerpark and price competitively to achieve >90% occupancy.
- **Path 2 (High-Margin):** Target larger, premium properties in central districts like Centrum-West and price for high margins.
