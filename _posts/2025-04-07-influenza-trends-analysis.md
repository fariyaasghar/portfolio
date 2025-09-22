---
layout: post
title: "Case Study: Public Health Analysis of Influenza Trends"
date: 2025-04-07
excerpt: "An analysis of CDC and Census data to build a data-driven blueprint for seasonal influenza preparedness, culminating in an interactive Tableau dashboard."
image:
  path: assets/images/thumbnails/influenza-thumbnail.png
  alt: A Tableau dashboard showing public health data.
tags: [Tableau, Excel, Data Integration, Statistical Analysis, Business Intelligence]
demo_link: https://public.tableau.com/shared/F6KRD2BBB?:display_count=n&:origin=viz_share_link
presentation_link: /assets/pdf/Fariya_Asghar_Portfolio_Deck.pdf # Path to the PDF
presentation_page: 9 # The slide number
---

### The Problem & Objective
Seasonal influenza places a predictable yet massive strain on healthcare systems. Public health officials need to make critical decisions about where to deploy limited resources, but often rely on incomplete data. My objective was to answer three core questions with data: **(1)** Who is most vulnerable? **(2)** When and where does the flu hit hardest? and **(3)** How can we build a data-driven framework for action?

**My Role:** Data Analyst  
**Context:** Solo project simulating a public health intelligence task.  
**Duration:** 3 Weeks  
**Tools:** Tableau (Data Integration, Blending, Interactive Dashboards), Excel, Statistical Analysis

---

### My Process: From Disparate Datasets to a Cohesive Strategy

The greatest challenge was the complex process of integrating three large, structurally different datasets to create a single, unified source of truth.

#### 1. Data Integration and Wrangling
I built a robust data pipeline, sourcing and blending three distinct datasets from the CDC and the U.S. Census Bureau. Using Excel and **Tableau's data blending capabilities**, I aligned them on a monthly basis and normalized mortality figures against population data to create accurate mortality rates, ensuring fair comparisons between states.

#### 2. Hypothesis Testing: Confirming the Greatest Risk Factor
**The "Aha!" Moment:** To test my hypothesis that age is the primary driver of flu-related mortality, I performed an **independent t-test**. The test yielded a **p-value of < 0.001**, providing statistically significant evidence that the elderly (65+) are disproportionately at risk. This confirmed they should be the top priority for any public health intervention.

<!-- ACTION: Place your bar chart image in /assets/images/ and name it influenza-age-chart.png -->
![Bar chart showing the higher mortality rate for the 65+ age group](/assets/images/influenza-age-chart.png)
*Above: The mortality rate for seniors was statistically significantly higher than for other age groups.*

#### 3. Mapping the Hotspots: Visualizing Seasonal and Geographic Peaks
With the "who" identified, I used **Tableau** to visualize the "when" and "where."
- **Seasonal Peaks:** A time-series chart revealed a clear and predictable surge in mortality every year, consistently peaking between **January and April**.
- **Geographic Disparities:** A geographic heat map highlighted that states like **California, Texas, and Florida** consistently showed the highest total mortality, making them priority regions.

<!-- ACTION: Place your Tableau map/line chart screenshot in /assets/images/ -->
![Tableau dashboard showing seasonal peaks and geographic hotspots for influenza](/assets/images/influenza-map-chart.png)
*Above: The Tableau visualization showing the annual Jan-Apr peak and identifying key hotspot states.*

---

### Final Solution: An Interactive Dashboard for Decision-Making

The final deliverable was a fully interactive **Tableau storyboard**. This tool empowers public health officials to explore the data themselves, filter by year or region, and understand the nuances of influenza trends in their specific area.

<!-- ACTION: Place your final Tableau dashboard screenshot in /assets/images/ -->
![Screenshot of the final interactive Tableau dashboard](/assets/images/influenza-dashboard.png)

#### Key Recommendations:
Based on the analysis, I proposed a 3-point action plan:
1.  **Prioritize the Elderly:** Focus vaccination campaigns and antiviral stockpiles on populations aged 65 and over.
2.  **Deploy Seasonally:** Proactively increase hospital staffing and distribute medical supplies in late December to prepare for the predictable January-April peak.
3.  **Target Geographically:** Allocate a greater share of federal resources to historically high-mortality states to bolster their healthcare capacity.

### Challenges & Lessons Learned
The primary challenge was the lack of granularity on comorbidities in the available data. This project was a powerful lesson in data integration; the real value came from combining multiple messy, real-world datasets to create a more complete picture, reinforcing that data wrangling is often the most critical part of a data analyst's job.
