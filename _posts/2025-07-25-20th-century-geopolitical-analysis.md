---
layout: post
title: "Case Study: Visualizing 20th Century Geopolitical Networks"
date: 2025-07-22
excerpt: "A demonstration of advanced data skills, using web scraping and Natural Language Processing (NLP) to analyze unstructured text and build a network visualization of historical country interrelations."
image:
  path: /assets/images/thumbnails/20th-century-thumbnail.png
  alt: A network graph of country relationships.
  popup: false
tags: [Python, NLP (spaCy), NetworkX, Pyvis, Web Scraping]
github_link: https://github.com/fariyaasghar/20th-century
---

### Overview
This project was a unique data science challenge: to model and visualize the complex, century-spanning interrelations between world powers. Starting with no structured data, I built a pipeline to scrape unstructured historical text, apply Natural Language Processing to extract relationships, and create a dynamic network graph to make these connections clear and interpretable.

### The Problem & Objective
The Institute for Public Policy hypothesized that the current geopolitical climate is heavily influenced by past events. The objective was to create a visual tool to help their researchers explore these historical ties. The core challenge was to create a structured dataset of country interactions from raw, narrative-based historical text.

##### **My Role:** I acted as the sole Data Analyst, responsible for the entire project from data acquisition to the final visualization.
##### **Duration:** 4 Weeks
##### **Tools:** Python, Web Scraping (BeautifulSoup), NLP (spaCy), NetworkX, Pyvis

---

<!-- This is the "Middle" of my case study -->

### The Process: Creating Structure from Chaos

#### 1. Data Sourcing and NLP
The project began by programmatically scraping historical text and a master list of countries from Wikipedia. I then used the **Python spaCy library** to perform **Named Entity Recognition (NER)**, a powerful NLP technique that identifies mentions of geopolitical entities (like countries) within the raw text. A significant data wrangling phase was required to standardize historical names (e.g., mapping "Soviet" to "Russia").

#### 2. Uncovering Geopolitical Blocs
I developed a custom script to analyze the co-occurrence of countries within the same sentences. This generated a structured "edge list" where each connection's weight was based on the frequency of interaction. When I visualized this network and applied the **Leiden algorithm for community detection**, a powerful insight emerged: **the algorithm, without any prior historical knowledge, successfully partitioned the countries into historically coherent blocs.**

<!-- ACTION: Place your final colored community graph in /assets/images/posts/ -->
![The final network graph showing distinct, color-coded geopolitical communities](/assets/images/geopolitics_network.png)
*Above: The final network visualization clearly showing a Central European/WWII bloc (blue), a Soviet/Eastern bloc (yellow), and a Post-Colonial/UK-Legacy bloc (red).*


#### 3. Quantifying Influence with Centrality Analysis
To identify the most influential nations in the network, I used **NetworkX** to calculate key centrality measures. The results consistently identified nations like Russia, Germany, and the UK as the most critical "hubs" and "bridges" in the 20th-century network, quantitatively confirming their pivotal historical roles.

<!-- ACTION: Place your centrality bar charts screenshot in /assets/img/posts/ -->
![Bar charts showing the top countries by Degree, Closeness, and Betweenness Centrality](/assets/images/geopolitics-centrality.png)
*Above: Centrality analysis provided a quantitative measure of influence for each nation.*

---

<!-- This is the "End" of my case study -->

### Final Solution & Findings
The final deliverable was an interactive network graph created with **Pyvis**, which allows users to explore the complex web of relationships visually. The analysis also included a quantitative ranking of the most influential nations using **NetworkX** to calculate centrality measures.

#### Key Findings:
1.  **Latent Structures in Text:** The success of the community detection algorithm proved that measurable patterns of historical alliances and conflicts can be extracted from unstructured text data.
2.  **Quantifying Influence:** Centrality analysis consistently identified nations like Russia, Germany, and the UK as the most critical "hubs" and "bridges" in the 20th-century network, quantitatively confirming their pivotal historical roles.

### Challenges & Lessons Learned
The greatest challenge was the ambiguity of historical text and the extensive data cleaning required to create a consistent set of entities for analysis. This project was a powerful lesson in the ability of NLP and network analysis to create valuable, structured insights from a source as seemingly chaotic as a historical article. It demonstrates a creative approach to problem-solving when a clean, pre-made dataset is not available.
