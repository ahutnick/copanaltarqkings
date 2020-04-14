---
layout: page
title: Motifs
permalink: /motif-glossary/
---

{% for entry in site.data.motif-glossary %}
  <p><strong>{{entry.Motif}}</strong> - {{entry.Meaning}}</p>
  <ul>
  <p>Monuments: <em>{{entry.Monuments}}</em></p>
  <p>Source: <em>{{entry.Source}}</em></p>
  </ul>
{% endfor %}
