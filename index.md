---
layout: default
title: "video List"
---


<div style="display: flex; flex-direction: column; gap: 30px; align-items: center;">
  {% for video in site.videos %}
  <div style="text-align: center;">
    <a href="{{ site.baseurl }}{{ video.url }}">
      <img src="{{ site.baseurl }}{{ video.thumbnail }}" alt="{{ video.title }}" 
           style="width: 100%; max-width: 1920px; height: auto; border-radius: 20px;">
    </a>
    <p style="font-size: 30px; font-weight: bold;">{{ video.title }}</p>
  </div>
  {% endfor %}
</div>

