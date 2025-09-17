---
layout: post
title: "Case Study: Predicting Bank Customer Churn with Machine Learning"
date: 2025-06-15
excerpt: "Developed a predictive model using Python and scikit-learn to proactively identify high-risk bank customers and guide targeted retention strategies."
image:
  path: assets/images/thumbnails/churn-thumbnail.png
  alt: A decision tree diagram for predicting customer churn.
  popup: false
tags: [Machine Learning, Python, scikit-learn, Predictive Analytics, Excel, Strategy]
github_link: https://github.com/fariyaasghar/nyc-citi-bike-dashboard
demo_link: https://nyc-citi-bike-dashboard.streamlit.app/
---

### The Problem & Objective
Pig E. Bank was losing customers but lacked a systematic way to understand why. Their retention efforts were reactive and ineffective. My objective was to answer the forward-looking question: **Can we predict which of our customers are most likely to leave, and what are the key warning signs?** The goal was to build an interpretable machine learning model to power a proactive retention program.

**My Role:** Data Analyst / Machine Learning Modeler  
**Context:** Capstone project focusing on the end-to-end predictive modeling process.  
**Duration:** 3 Weeks  
**Tools:** Python (scikit-learn, Pandas), Jupyter Notebook, Excel

---

### My Process: Building a Bridge from Data to Prediction

My approach was to first understand the data through exploratory analysis in Excel and then use those insights to build and interpret a predictive model in Python.

#### 1. Exploratory Data Analysis (EDA) in Excel
I began by using Excel pivot tables to perform an initial exploration of the dataset, which revealed that certain groups—particularly inactive members and those in specific geographic locations—had a higher churn rate. This validated the data's potential for a predictive model.

#### 2. Building and Interpreting the Decision Tree
The core of the project was to move from "what happened" to "what will happen." I used Python's **scikit-learn** library to develop a **Decision Tree** classification model, chosen specifically for its high interpretability.

**The Core Insight:** The trained model immediately identified the single most powerful predictor of churn: **being an 'Inactive Member'** dramatically increases the likelihood of leaving. The model's logic was clear: for inactive members, other factors like having a high balance and being middle-aged were also significant secondary predictors.

<!-- ACTION: Place your Decision Tree image in /assets/images/ and name it churn-decision-tree.png -->
![The final Decision Tree model generated in Python](/assets/images/churn-decision-tree.png)
*Above: The interpretable Decision Tree model, which clearly shows the key drivers of customer churn.*

#### 3. Synthesizing the Findings: The 'At-Risk' Customer Persona
A model's predictions are only useful if they can be translated into business action. I synthesized all findings to create a detailed, data-driven customer persona.

**The "At-Risk" Persona:**
- **Status:** Inactive Member (70% of churned customers are inactive).
- **Demographics:** Middle-Aged (40-60), often Female, and residing in Germany.
- **Financials:** Holds a High Balance (typically $100k - $200k).

**The Counter-Intuitive Learning:** The greatest financial risk came not from new customers, but from established, high-balance members who had become disengaged.

<!-- ACTION: Place your "At-Risk" persona graphic in /assets/images/ -->
![A graphic summarizing the key attributes of the 'At-Risk' Customer Persona](/assets/images/churn-persona.png)
*Above: The final persona, combining demographic and behavioral data to create a clear target for retention efforts.*

---

### Final Solution: A Proactive Strategy to Reduce Churn

The final deliverable was a Jupyter Notebook containing the full model development process and a presentation outlining a new, proactive retention strategy based on the model's insights.

#### Key Recommendations:
1.  **Launch Targeted Re-Engagement Campaigns:** Proactively contact customers flagged by the model as "at-risk" (inactive, high-balance) with personalized offers and financial consultations.
2.  **Develop a Regional Strategy:** Since German customers showed a higher propensity to churn, investigate region-specific issues and create tailored marketing campaigns.
3.  **Innovate for the Core Persona:** Design new products and services that cater specifically to the financial goals of middle-aged, high-balance customers, such as advanced investment tools.

### Challenges & Lessons Learned
The key challenge was translating initial hypotheses into a functional and accurate model using **scikit-learn**. This project was a powerful lesson in the difference between analysis and prediction. I learned that the true value of a model is not just its accuracy, but its **interpretability**—the ability to explain *why* it makes its predictions is crucial for gaining business trust and driving real-world action.
