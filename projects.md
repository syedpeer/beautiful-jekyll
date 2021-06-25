---
layout: page
title: Projects
---

{% for projects in site.projects %}

<div>
  <h2><a href="{{ projects.url }}">{{ projects.title }}</a></h2>
</div>

<p class="post-excerpt">{{ projects.description | truncate: 160 }}</p>

{% endfor %}  