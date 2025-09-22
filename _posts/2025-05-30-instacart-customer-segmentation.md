---
layout: post
title: "Case Study: Instacart Grocery Basket Analysis"
date: 2025-05-30
excerpt: "A Python-based analysis of 32 million Instacart orders to uncover customer purchasing patterns and develop a core customer persona for targeted marketing."
image:
  path: assets/images/thumbnails/instacart-thumbnail.png
  alt: A chart showing customer purchasing data.
tags: [Python, Pandas, Matplotlib, Seaborn, Customer Segmentation, Data Wrangling]
github_link: https://github.com/fariyaasghar/InstacartGroceryBasketAnalysis
presentation_link: /assets/pdf/Fariya_Asghar_Portfolio_Deck.pdf # Path to the PDF
presentation_page: 19 # The slide number
---

### The Problem & Objective
In the competitive online grocery market, Instacart needed to deeply understand its customer base. My objective was to analyze a massive dataset of over 32 million orders to answer three fundamental questions: **(1)** What are the key temporal patterns of shopping behavior? **(2)** Which product categories drive sales? and **(3)** Can we define a "core customer" persona to focus marketing efforts?

**My Role:** Data Analyst  
**Context:** Solo project focused on large-scale data wrangling and customer segmentation with Python.  
**Duration:** 4 Weeks  
**Tools:** Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook, Excel

---

### My Process: From 32 Million Rows to a Single, Clear Persona

The primary challenge was the sheer scale and complexity of the data, which required a rigorous data wrangling pipeline followed by systematic exploratory analysis.

#### 1. Data Wrangling and Engineering at Scale
The project involved integrating multiple large datasets. Using the **Python Pandas library**, I performed extensive data wrangling, including merging dataframes, checking for data consistency, handling missing values, and deriving new variables like customer loyalty flags. This foundational work was critical for ensuring the integrity of the subsequent analysis.

<!-- ACTION: Place your "Population Flow" diagram in /assets/images/ and name it instacart-data-flow.png -->
![A diagram showing the data wrangling and integration process for the Instacart datasets](/assets/images/instacart-data-flow.png)
*Above: The data wrangling pipeline used to merge and clean the multiple source files.*

#### 2. Finding the Pulse: Peak Shopping Times & Top Categories
My first analytical step was to identify broad behavioral patterns. The analysis revealed undisputed peak shopping periods on **weekends (Saturday/Sunday) and midday (9 AM - 4 PM)**. The top-selling departments were consistently **Produce, Dairy/Eggs, and Snacks**, indicating a high demand for everyday essentials.

<!-- ACTION: Place your dashboard view of the two charts in /assets/images/ -->
![A side-by-side view of charts showing peak shopping days and top product departments](/assets/images/instacart-peak-times.png)
*Above: Visualizations highlighting peak shopping times and top-selling product categories.*

#### 3. A Pivotal Finding: Building the Core Customer Persona
The most valuable insight came from connecting behavioral data with demographic data. The analysis revealed a powerful and consistent customer persona: **"The Savvy Parent."** This segment—defined as married, middle-income, with dependents—forms the largest and most loyal customer group. Their shopping behavior is distinct: they prioritize fresh, healthy, and organic options for their families.

By defining this persona, I provided the marketing team with a clear, data-driven target for all future campaigns, promotions, and product recommendations.

<!-- ACTION: Place your composite image of the three persona charts in /assets/images/ -->
![A composite image of charts showing family status, income, and top products for the 'Savvy Parent' persona](/assets/images/instacart-persona-charts.png)
*Above: The key demographic and purchasing charts used to build the "Savvy Parent" persona.*

---

### Final Solution: A Data-Driven Blueprint for Marketing & Sales

My analysis translated millions of data points into a clear and actionable strategic blueprint, delivered as a comprehensive Jupyter Notebook and a presentation for the marketing and sales teams.

#### Key Recommendations:
1.  **Target the "Savvy Parent" Persona:** Launch targeted campaigns like "Weekly Family Meal" bundles and "Healthy Kids Lunchbox" promotions featuring top organic products.
2.  **Optimize Ad Spend & Promotions:** Focus the majority of the ad budget on weekends between 9 AM and 4 PM, with smaller, targeted promotions for other segments.
3.  **Increase Average Order Value:** Implement a "Goes well with..." recommendation engine to logically cross-sell items (e.g., suggest "Organic Berries" when a user adds "Yogurt" to their cart).

### Challenges & Lessons Learned
Working with a dataset of this size required writing efficient, optimized Pandas code to avoid memory errors. This project was a testament to the 80/20 rule of data analysis: 80% of the work was in the meticulous data cleaning and preparation, but that rigorous upfront work is what enabled the final analysis and persona development to be both accurate and incredibly valuable.
