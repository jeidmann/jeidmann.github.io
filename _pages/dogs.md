---
layout: page
permalink: /dogs/
title: dogs
description:
years: [2025, 2024]
nav: true
nav_order: 3
---
<!-- _pages/dogs.md -->
<div class="dogs">

After we lost our two St.Bernards to bone cancer within a half year of each other, we weren't quite ready to get another dog but wanted to help dogs in need. Since June 2024, we have fostered dogs with `Big Bones Canine Rescue` in Northern Colorado. Below is a list of the dogs that we have helped find a `forever home`.

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f dogs -q @*[year={{y}}]* %}
{% endfor %}

</div>

---

