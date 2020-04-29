---
layout: default
title: Seldovia People
---

{% for people in site.people %}

<a href="{{ people.url | prepend: people.baseurl }}">
  <h2>{{ people.title }}</h2>
</a>

{% endfor %} 
