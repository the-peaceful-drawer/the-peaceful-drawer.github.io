---
layout: page
title: "Ngoại ngữ"
permalink: /chinh-phuc/ngoai-ngu/
---
<ul class="post-list">
  {% for post in site.categories['ngoai-ngu'] %}
  <li>
    <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
    <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
  </li>
  {% endfor %}
</ul>