---
layout: page
title: Projects
---

{% for project in site.projects %}

<div>
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
</div>

<p class="post-excerpt">{{ project.description | truncate: 160 }}</p>

{% endfor %}  