---
layout: home
title: "My v_test site"
---

# video list

{% for video in site.videos %}
- [{{ video.title }}]({{ site.baseurl }}{{ video.url }})
{% endfor %}
