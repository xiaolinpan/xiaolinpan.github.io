---
layout: page
permalink: /publications/
title: Publications
description: 18 peer-reviewed papers (6 first-author). * corresponding author; † trainee mentored by me. Also see <a href='https://scholar.google.com/citations?user=-vCSDe0AAAAJ&hl=en'>Google Scholar</a>.
years: [2026, 2025, 2024, 2023, 2022, 2021, 2020]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
