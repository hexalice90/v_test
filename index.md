---
layout: default
title: "video List"
---


{% for video in site.videos %}
- [{{ video.title }}]({{ site.baseurl }}{{ video.url }})
{% endfor %}
