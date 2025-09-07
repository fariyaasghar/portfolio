---
layout: post
title: "Case Study: Visualizing 20th Century Geopolitical Networks"
date: 2025-07-22
categories: [Data Science, NLP]
tags: [Python, spaCy, NetworkX, Pyvis, Web Scraping]
image:
  path: /assets/images/thumbnails/geopolitics-network.png # Use a descriptive image name
  alt: A network graph of country relationships.
---
github_link: https://github.com/fariyaasghar/20th-century
---

### The Challenge

The Institute for Public Policy sought a novel way to understand the historical ties between different countries. My objective was to scrape unstructured historical text from the web, use Natural Language Processing to extract a "relationships map," and create a dynamic network visualization to make these historical connections clear and analyzable.

### The Process

The project involved a full data science pipeline, including programmatic **Web Scraping** from Wikipedia, applying the **spaCy** library for Named Entity Recognition (NER), and developing a custom script to extract co-occurrence relationships. The final network was constructed with **NetworkX** and visualized with **Pyvis**.

### Key Insights & Visualizations

#### 1. Uncovering Geopolitical Blocs with Community Detection
The most powerful insight came from applying the Leiden algorithm for community detection to the network. The algorithm, without any prior historical knowledge, successfully partitioned the countries into historically coherent blocs, as seen in the visualization below.

![Screenshot of the Community Detection Network Graph](/assets/images/geopolitics_network.png)

#### 2. Identifying the Century's Most Influential Nations
Centrality analysis provided a quantitative measure of influence. The charts show that nations like Russia, Germany, and France consistently ranked at the top, confirming their pivotal roles in the century's major events.

![Screenshot of the Centrality Bar Charts](/assets/images/geopolitics_centrality_1.png)

### Project Reflection

This project was a fantastic challenge in end-to-end data analysis, starting with no data and ending with a rich, interactive visualization. A key takeaway was the incredible power of network analysis to distill complex, narrative-based information into a structured and quantifiable format.
