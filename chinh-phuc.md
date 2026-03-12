---
layout: page
title: "Chinh phục"
permalink: /chinh-phuc/
---

<section class="conquest-section">
  <h2 class="section-title">01. Ngoại ngữ</h2>
  <ul class="post-list">
    {% for post in site.categories['ngoai-ngu'] %}
    <li>
      <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
      <p>{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
    </li>
    {% endfor %}
  </ul>
</section>

<hr style="margin: 40px 0; border: 0; border-top: 1px dashed #ccc;">

<section class="conquest-section">
  <h2 class="section-title">02. Kiến thức mới</h2>
  <ul class="post-list">
    {% for post in site.categories['kien-thuc-moi'] %}
    <li>
      <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
      <p>{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
    </li>
    {% endfor %}
  </ul>
</section>