---
layout: page
permalink: /publications/
title: Publications
description: Latest research group publications.
years: [2022,2020,2018]
nav: true
nav_order: 4
---
This are the most recenct publications from our research group. The full list of publications can be found [here](https://pure.fh-ooe.at/de/organisations/smart-mechatronics-engineering/publications/).

## Papers and Articles
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

## Books
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f books %}

</div>