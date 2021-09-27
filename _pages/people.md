---
layout: page
title: People
permalink: /people/
description:
nav: true
display_categories: [Faculty, Students, Staff, Alumni]
order: 1
---
<div class="people">
  <!-- Display categorized people -->
  {% for category in page.display_categories %}
    <h2 class="category">{{category}}</h2>
    {% assign categorized_people = site.people | where: "category", category %}
    {% assign sorted_people = categorized_people | sort: "importance" %}
    <!-- Generate cards for each person -->
    <div class="grid">
      {% for people in sorted_people %}
        {% include people.html %}
      {% endfor %}
    </div>
  {% endfor %}
</div>
