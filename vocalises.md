---
layout: page
title: Vokaliisit
permalink: /vocalises
---

<ol>
  {% for vocalise in site.vocalises %}
    <li>
      <a href="{{site.baseurl}}{{vocalise.url}}">{{vocalise.title}}</a>
    </li>
  {% endfor %}
</ol>
