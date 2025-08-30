---
layout: page
title: People
permalink: /people/
description:
nav: true
display_categories: [Faculty, Students]
order: 1
---
<div class="people">
  <!-- Display categorized people -->
    <!--h2 class="category">{{category}}</h2-->
    {% assign sorted_people = site.people | sort: "sequence" %}
    <!-- Generate cards for each person -->
    <div class="grid">
      {% for people in sorted_people %}
        {% include people.html %}
      {% endfor %}
    </div>
    <h2 class="category">Alumni</h2>
      <ul>
        <li><a href="https://curie3170.github.io/" target="_blank">Curie Kim</a> (Research Staff, 2022-2023) → Ph.D. Course@University of Maryland</li>
      </ul>
</div>
