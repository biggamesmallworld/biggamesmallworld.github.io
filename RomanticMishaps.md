---
layout: page
permalink: /categories/Romance
title: Romantic Mishaps
---

<div class="categoryContainer">
  {% for post in site.categories.Romance %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a>
    <article class="archive-item">
      <p>{{ post.excerpt }}</p>
    </article>
  </li>
  {% endfor %}
</div>