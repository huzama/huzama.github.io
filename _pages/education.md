---
layout: page
title: education
nav: true
permalink: /education/
display_categories: [school, certificates]
nav_order: 2
---


<div class="education">
  {%- for category in page.display_categories %}
    <h2 class="category">{{ category }}</h2>
    {% for repo in site.data.education %}
      <h3> {{ site.data.education.school.Name }} </h3>
    {% endfor %}
  {% endfor %}
</div>