---
layout: page
title: "Seldovia People"
permalink: "/people/"
---

<ul>
  {% for people in site.people %}
    <li>
      <a href="{{ people.url }}">{{ people.title }}</a>
      - {{ people.birth_date }}
    </li>
  {% endfor %}
</ul>
