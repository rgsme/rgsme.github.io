---
layout: page
permalink: /publications/
title: Publications
description:
years: [2024, 2023, 2022, 2021, 2020]
nav: true
nav_order: 6
---

This are the most recent publications from our research group. The full list of publications can be found [here](https://pure.fh-ooe.at/de/organisations/smart-mechatronics-engineering/publications/).

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
