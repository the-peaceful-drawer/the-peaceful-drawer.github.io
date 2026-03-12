---
layout: page
title: "Tùy hứng Vlog"
permalink: /tuy-hung-vlog/
---
<ul class="post-list">
  {% for post in site.categories['tuy-hung-vlog'] %}
  <li>
    <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
    <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
  </li>
  {% endfor %}
</ul>