---
layout: default
title: Home
---

<h2>Projects</h2>
<ul>
{% for project in site.projects %}
  <li>
    <a href="{{ project.url }}">
      <img src="{{ project.image }}" alt="{{ project.title }}" width="100">
      {{ project.title }}
    </a>
  </li>
{% endfor %}
</ul>
