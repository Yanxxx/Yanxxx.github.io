---
layout: default
title: Yan Li
---
<section id="home" class="intro-carousel-container">
    {% include intro.html %}
</section>


<section id="Personal-Projects">
    {% include pet-projects.html %}
</section>

<section id="Resilient-Seedling">
    {% include ai-forestry.html %}
</section>

<section id="Assistant-Robots">
    {% include assistant-robot.html %}
</section>

<section id="Few-Shot-Robot-Task-Learning">
    {% include robot-task-learning.html %}
</section>

<section id="L2-Autonomous-Driving">
    {% include autonomous-driving.html %}
</section>

<section id="Blind-Navigation">
    {% include blind-navigation.html %}
</section>

<!-- <h2>Projects</h2>
<ul>
{% for project in site.projects %}
  <li>
    <a href="{{ project.url }}">
      <img src="{{ project.image }}" alt="{{ project.title }}" width="100">
      {{ project.title }}
    </a>
  </li> -->
{% endfor %}
</ul>
