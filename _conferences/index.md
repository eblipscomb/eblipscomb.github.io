---
layout: default
title: My Collection of Notes
permalink: :collection
---

# All My Notes
<ol>
  {% for item in site.conferences %}
  <li><a href="{{item.url}}">{{ item.title }}</a></li>
</ol>
