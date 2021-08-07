---
layout: page
title: Projects
---

{% for project in site.projects %}

<!--
<div>
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
</div>
-->

<a href="{{ project.url | absolute_url }}">
  <h2 class="post-title">{{ project.title }}</h2>
  {% if project.subtitle %}
    <h3 class="post-subtitle">
    {{ project.subtitle }}
    </h3>
  {% endif %}
</a>

<p class="post-meta">
  {% assign date_format = site.date_format | default: "%B %-d, %Y" %}
  Posted on {{ project.date | date: date_format }}
</p>

<p class="post-excerpt">{{ project.description | truncate: 160 }}</p>

{% endfor %}  