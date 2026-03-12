---
layout: page
title: "Nhà và bé"
permalink: /nha-va-be/
---
<ul class="post-list">
  {% for post in site.categories['nha-va-be'] %}
  <li>
    <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
    <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
  </li>
  {% endfor %}
</ul>