---
layout: page
title: Blog
permalink: /blog/
---

A collection of some of my thoughts that I've penned!


<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>


<br><br><br>

ToDos/Ideas:
=====

1. Complete Bessel's correction
2. Why do cross validation before doing feature selection in wide data sets
3. <del>PhD application story</del>
4. BayesPy
