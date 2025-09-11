---
title: Projects
icon: fas fa-briefcase
order: 2
layout: page
---

Welcome to my project portfolio. Each project demonstrates different aspects of the data analytics workflow, from data collection and cleaning to analysis, visualization, and business recommendations.

Here you will find a complete list of my data analysis case studies. Each project showcases a different aspect of the data science workflow.

<hr>

<div id="post-list" class="row row-cols-1 row-cols-md-2 g-4">
  {% for post in site.posts %}
    <div class="col">
      {% include post-card.html %}
    </div>
  {% endfor %}
</div>
