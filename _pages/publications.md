---
layout: page
permalink: /research/
title: Research
description:
years: [2023, 2022, 2021]
nav: true
nav_order: 1
---

<div style="text-align: justify">

My research focuses on nonlinear control, optimization and learning-based methods. 
<br>
<br>
Checkout my <a href='https://scholar.google.com/citations?user=GO2TUxMAAAAJ&hl=en&oi=ao'>Scholar</a> page for an updated list of publications.
<br>
</div>
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
