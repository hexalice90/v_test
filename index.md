---
layout: default
title: "video List"
---

{% for video in site.videos %}
  <br>
  <li style="font-size: 50px;">
    <a href="{{ site.baseurl }}{{ video.url }}">{{ video.title }}</a>
  </li>
{% endfor %}
