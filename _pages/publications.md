---
layout: page
permalink: /publications/
title: publications
description: <a href="#journals">Journals</> / <a href="#conf">Conferences</a> / <a href="#thesis">PhD Thesis</a> / <a href="#others">Workshops and Demonstrations</a> / <a href="#patents">Patents</>
j_years: [2020, 2019, 2014, 2012]
c_years: [2019, 2018, 2017, 2016, 2012, 2011]
t_years: [2014]
o_years: [2016,2013]
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

#### <a name="others"></a> Workshops / Demonstrations 

{% for y in page.o_years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f others -q @*[year={{y}}]* %}
{% endfor %}

#### <a name="patents"></a> Patents

More than 20 patents were filled. The list can be found [here](https://worldwide.espacenet.com/searchResults?ST=singleline&locale=en_EP&submitted=true&DB=&query=danieau+fabien)