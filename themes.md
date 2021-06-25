---
layout: page
title: Themes
---

{% for themes in site.themes %}

<!---
<a href="{{ themes.url | prepend: site.baseurl }}">
  <h2>{{ themes.title }}</h2>
</a>
--->
<div>
  <h2><a href="{{ themes.url }}">{{ themes.title }}</a></h2>
</div>

<p class="post-excerpt">{{ themes.description | truncate: 160 }}</p>

{% endfor %}  