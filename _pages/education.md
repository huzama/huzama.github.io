---
layout: page
title: education
nav: true
permalink: /education/
display_categories: [school, certificates]
nav_order: 2
---


<div class="education">
    <h2 class="category">{{ page.display_categories[0] }}</h2>
    {% for school in site.data.education.school %}
      {% include education/school.html school=school %}
    {% endfor %}

    <h2 class="category">{{ page.display_categories[1] }}</h2>
    {% for certificates in site.data.education.certificates %}
      {% include education/certificates.html certificates=certificates %}
    {% endfor %}
</div>