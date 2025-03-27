---
layout: default
title: "video List"
---


<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  {% for video in site.videos %}
  <div style="text-align: center;">
    <a href="{{ site.baseurl }}{{ video.url }}">
      <img src="{{ site.baseurl }}{{ video.thumbnail }}" alt="{{ video.title }}" 
           style="width: 200px; height: auto; border-radius: 10px;">
    </a>
    <p>{{ video.title }}</p>
  </div>
    <li style="font-size: 50px;">
    <a href="{{ site.baseurl }}{{ video.url }}">{{ video.title }}</a>
  </li>
  {% endfor %}

</div>

