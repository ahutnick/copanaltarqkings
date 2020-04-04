---
layout: page
title: Glossary
permalink: /glossary/
---

{% for entry in site.data.glossary %}
  <p><strong>{{entry.Term}}</strong> - {{entry.Definition}}</p>
  <ul>
  <li>{{entry.Source}}</li>
  </ul>
{% endfor %}
