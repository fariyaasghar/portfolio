---
title: Projects
icon: fas fa-briefcase
order: 2
layout: page
---
<h1>Data Analytics Projects</h1>
<p class="fs-5 text-muted">Welcome to my project portfolio. Each project demonstrates different aspects of the data analytics workflow, from data collection and cleaning to analysis, visualization, and business recommendations.</p>
<div id="post-list" class="row row-cols-1 row-cols-md-2 g-4 mt-4">
  {% for post in site.posts %}
    <div class="col">
      {% include post-card.html %}
    </div>
  {% endfor %}
</div>