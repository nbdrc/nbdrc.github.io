---
layout: page
permalink: /publications/
title: Publications
description: Under Construction
years: [1956, 1950, 1935, 1905]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
