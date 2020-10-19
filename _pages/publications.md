---
layout: page
permalink: /publications/
title: publications
years: [2020, 2019, 2017, 2011, 2010, 2008]
nav: true
---

<em class="star">*</em> denotes equal contribution

An up-to-date list is available on [Google Scholar](https://scholar.google.com/citations?user=8osGCyAAAAAJ){:target="\_blank"}.



<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
