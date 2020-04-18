---
layout: page
permalink: /publications/
title: publications
description: <a href="#journals">Journals</> / <a href="#conf">Conferences</a> / <a href="#thesis">PhD Thesis</a>
j_years: [2020, 2019, 2014, 2012]
c_years: [2019, 2018, 2017, 2016, 2014, 2012, 2011]
t_years: [2014]
---

#### <a name="journals"></a> Journals

{% for y in page.j_years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f journal -q @*[year={{y}}]* %}
{% endfor %}

#### <a name="conf"></a> Conferences

{% for y in page.c_years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f conference -q @*[year={{y}}]* %}
{% endfor %}

#### <a name="thesis"></a> PhD Thesis 

{% for y in page.t_years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f thesis -q @*[year={{y}}]* %}
{% endfor %}