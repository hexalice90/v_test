---
layout: default
title: "video List"
---

<ul>
{% for video in site.videos %}
  <li style="font-size: 20px;">
    <a href="{{ site.baseurl }}{{ video.url }}">{{ video.title }}</a>
  </li>
{% endfor %}
</ul>
