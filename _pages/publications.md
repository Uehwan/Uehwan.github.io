---
layout: page
permalink: /publications/
title: Publications
years: [2024, 2023, 2022, 2021, 2020]
prev_years: [2018, 2017, 2016, 2015, 2014]
nav: true
order: 2
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h2 class="year">2014 - 2018</h2>
{% for y in page.prev_years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
