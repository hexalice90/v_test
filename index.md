---
layout: default
title: "video List"
---


<div style="display: flex; flex-direction: column; gap: 30px; align-items: center;">
  {% for video in site.videos %}
  <div style="text-align: center;">
    <a href="{{ site.baseurl }}{{ video.url }}">
      <img src="{{ site.baseurl }}{{ video.thumbnail }}" alt="{{ video.title }}" 
           style="width: 100%; max-width: 1920px; height: auto; border-radius: 10px;">
    </a>
    <p style="font-size: 40px; font-weight: bold;">
      <a href="{{ site.baseurl }}{{ video.url }}" style="text-decoration: none; color: black;">
        {{ video.title }}
      </a>
    </p>
  </div>
  {% endfor %}
</div>

