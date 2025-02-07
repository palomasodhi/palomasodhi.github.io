---
layout: page
permalink: /papers/
title: papers
description: full list at <a href="https://scholar.google.com/citations?user=LI7rp1QAAAAJ&hl=en">google scholar</a>
years: [2024, 2023, 2022, 2021]
nav: false
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>