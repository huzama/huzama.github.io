---
layout: page
title: experience
permalink: /experience/
display_categories: [Work, Volunteer]
nav: true
nav_order: 3
---

<div class="experience">
  {%- for category in page.display_categories %}
    <h2 class="category">{{ category }}</h2>
    {% for repo in site.data.experience %}
      <h3> {{ site.data.experience.work.Name }} </h3>
    {% endfor %}
  {% endfor %}
</div>