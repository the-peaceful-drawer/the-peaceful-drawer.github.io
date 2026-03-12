---
layout: page
title: "Học Cách Sống"
permalink: /hoccachsong/
---
<ul class="post-list">
  {% for post in site.categories['hoccachsong'] %}
  <li>
    <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
    <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
  </li>
  {% endfor %}
</ul>