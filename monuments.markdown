---
layout: page
title: Monuments List
permalink: /monuments/
---

{% for monument in site.monuments %}
  <p><a href="{{site.baseurl}}{{monument.permalink}}">
      {{monument.title}}</a></p>
{% endfor %}

## Structures

{% for structure in site.structures %}
  <p><a href="{{site.baseurl}}{{structure.permalink}}">
      {{structure.title}}</a></p>
{% endfor %}
