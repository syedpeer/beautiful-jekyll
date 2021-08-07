---
layout: page
title: Projects
---

{% for project in site.projects %}


<div>
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
  {% if project.subtitle %}
    <h3 class="project-subtitle">
    {{ project.subtitle }}
    </h3>
  {% endif %}  
</div>

<p class="post-meta">
  {% assign date_format = site.date_format | default: "%B %-d, %Y" %}
  Posted on {{ project.date | date: date_format }}
</p>

<p class="post-excerpt">{{ project.description | truncate: 160 }}</p>

{% endfor %}  