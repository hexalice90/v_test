---
layout: default
title: My v_test site
---

<h1>MP4 Video Gallery</h1>
<ul>
  {% for video in site.videos %}
    <li><a href="{{ video.url }}">{{ video.title }}</a></li>
  {% endfor %}
</ul>
