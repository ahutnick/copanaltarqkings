---
layout: page
title: Motifs
permalink: /motif-glossary/
---

{% for entry in site.data.motif-glossary %}
  <p><strong>{{entry.Motif}}</strong> - {{entry.Meaning}}</p>
  <ul>
  <p>Monuments:</p>
  <ul>
  <li>{{entry.Monuments}}</li>
  </ul>
  <p>Source:</p>
  <ul>
  <li>{{entry.Source}}</li>
  </ul>
  </ul>
{% endfor %}
