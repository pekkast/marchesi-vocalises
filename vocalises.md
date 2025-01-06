---
layout: page
title: Vokaliisit
permalink: /vocalises
---

<ol>
  {% for vocalise in site.vocalises %}
    <li>
      <a href="{{ vocalise.url | relative_url }}">{{ vocalise.title }}</a>
    </li>
  {% endfor %}
</ol>
