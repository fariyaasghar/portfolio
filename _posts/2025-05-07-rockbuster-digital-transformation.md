---
layout: post
title: "Case Study: Rockbuster Movie Rentals' Digital Transformation"
date: 2025-05-07
excerpt: "An SQL-driven analysis of a large PostgreSQL database to guide a traditional company's pivot to an online video rental service."
image:
  path: assets/images/thumbnails/rockbuster-thumbnail.png
  alt: A chart showing regional revenue data for a movie rental company.
tags: [SQL, PostgreSQL, Tableau, Excel, Business Intelligence, Strategy]
github_link: https://github.com/fariyaasghar/RockbusterStealthLLC.OnlineLaunchStrategy
demo_link: https://public.tableau.com/shared/ZWPRKXQ92?:display_count=n&:origin=viz_share_link
presentation_link: /assets/pdf/Fariya_Asghar_Portfolio_Deck.pdf # Path to the PDF
presentation_page: 14 # The slide number
---

### The Problem & Objective
Rockbuster, a traditional movie rental company, faced extinction from streaming giants. To survive, they needed to pivot to an online model. My objective was to analyze their historical customer and sales data to answer critical strategic questions: **(1)** Where are our most valuable customers? **(2)** What content is most profitable? and **(3)** How can we optimize pricing for a digital launch?

**My Role:** Data Analyst & Strategist  
**Context:** Solo project focused on advanced SQL and business intelligence.  
**Duration:** 3 Weeks  
**Tools:** SQL (PostgreSQL), Tableau, Excel, PowerPoint

---

### My Process: Querying the Database for Insights

The foundation of this project was directly accessing and manipulating a complex relational database using **advanced SQL queries** to synthesize information from multiple tables and generate key business metrics.

<!-- ACTION: Place your SQL code screenshot in /assets/images/ and name it rockbuster-sql-code.png -->
![A screenshot of a complex SQL query using JOINs and CTEs](/assets/images/rockbuster-sql-code.png)
*Above: An example of the SQL queries used to join customer, rental, and payment tables.*

#### The Core Insight: Revealing the Dominant Market
The most critical strategic question was where to focus the initial launch. I aggregated revenue data by country, revealing a game-changing fact: **Asia was Rockbuster's hidden goldmine**, accounting for nearly 40% of all global revenue. This insight immediately established that an Asia-first launch strategy was the optimal path forward.

<!-- ACTION: Place your bubble chart image in /assets/images/ and name it rockbuster-bubble-chart.png -->
![A bubble chart showing regional revenue, with Asia as the largest bubble](/assets/images/rockbuster-bubble-chart.png)
*Above: The Regional Revenue Analysis clearly showing Asia's market dominance.*

#### Drilling Deeper: Content and Pricing Opportunities
Knowing where to launch, I then focused on what to offer.
- **Content Performance:** An analysis of film categories showed that **Sports, Sci-Fi, and Animation** were the most consistently profitable genres.
- **Pricing Opportunity:** I discovered a clear opportunity to implement dynamic pricing by identifying high-demand films that were currently priced at the lowest tier (€0.99).

---

### Final Solution: A 3-Point Strategy for a Successful Launch

My analysis culminated in a clear, actionable, and data-driven 3-point strategy, which I delivered as an executive-level presentation supported by an interactive **Tableau dashboard**.

<!-- ACTION: Place your final Tableau dashboard screenshot in /assets/images/ -->
![Screenshot of the final interactive Tableau dashboard for Rockbuster](/assets/images/rockbuster-dashboard.png)

#### Key Recommendations:
1.  **Prioritize Asia-Focused Growth:** Launch first in key Asian markets like India and China, localizing the platform with regional payment options and content.
2.  **Optimize Pricing & Introduce Bundles:** Test a 20% price increase on high-demand €0.99 films and introduce a "Binge Pass" bundle to increase average revenue per user.
3.  **Drive Loyalty with Top Content:** Heavily promote the top-performing genres (Sports, Sci-Fi) and implement a simple loyalty program to retain the existing customer base.

### Challenges & Lessons Learned
The primary challenge was writing efficient queries to join multiple large tables without performance issues, which required careful planning and the use of **Common Table Expressions (CTEs)**. This project was a powerful demonstration of how raw SQL skills can directly translate into high-level business strategy, proving that the most valuable insights are often hidden in the relationships between different data tables.
