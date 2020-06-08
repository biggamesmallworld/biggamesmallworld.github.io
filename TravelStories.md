---
layout: page
permalink: /categories/Travel
title: Travel Stories
---

<div class="categoryContainer">
  {% for post in site.categories.Travel %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a>
    <article class="archive-item">
      <p>{{ post.excerpt }}</p>
    </article>
  </li>
  {% endfor %}
</div>