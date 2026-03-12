---
layout: page
title: "Học Cách Sống"
permalink: /hoc-cach-song/
---
<ul class="post-list">
  {% for post in site.categories['hoc-cach-song'] %}
  <li>
    <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
    <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
  </li>
  {% endfor %}
</ul>