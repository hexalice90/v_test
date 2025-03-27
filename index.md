---
layout: default
title: "video List"
---


<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  {% for video in site.videos %}
  <div style="text-align: center;">
    <a href="{{ site.baseurl }}{{ video.url }}">
      <img src="{{ site.baseurl }}{{ video.thumbnail }}" alt="{{ video.title }}" 
           style="width: 100%; max-width: 1920px; height: auto; border-radius: 10px;">
    </a>
    <p>{{ video.title }}</p>
  </div>
  {% endfor %}

</div>

