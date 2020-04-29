---
layout: default
title: "Seldovia People"
---

<ul>
  {% for people in site.people %}
    <li>
      <a href="{{ people.url }}">{{ people.title }}</a>
      - {{ people.birth_date }}
    </li>
  {% endfor %}
</ul>
