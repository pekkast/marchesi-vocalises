---
layout: page
title: Vokaliisit
permalink: /vocalises
---

<ol>
  {% assign vocalises = site.vocalises | sort: "orderNo" %} 
  {% for vocalise in vocalises %}
    <li>
      <a href="{{ vocalise.url | relative_url }}">{{ vocalise.title }}</a>
    </li>
  {% endfor %}
</ol>
