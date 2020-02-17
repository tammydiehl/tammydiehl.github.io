---
layout: archive
title: "Data Visualization"
permalink: /datavisualization/
author_profile: true
---

This is a page for my data visualizations.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>