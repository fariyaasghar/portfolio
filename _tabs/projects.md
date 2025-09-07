---
title: Projects
icon: fas fa-briefcase
order: 2
layout: page
---

Welcome to my project portfolio. Each project demonstrates different aspects of the data analytics workflow, from data collection and cleaning to analysis, visualization, and business recommendations.

Here you will find a complete list of my data analysis case studies.

<hr>

<div class="post-list">
  {% for post in site.posts %}
    <div class="post-preview">
      <h3 class="post-title">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      <div class="post-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
      </div>
      <div class="post-content">
        {{ post.excerpt }}
      </div>
    </div>
  {% endfor %}
</div>
