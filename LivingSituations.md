---
layout: page
permalink: /categories/Living
title: Living Situations
---

<div class="categoryContainer">
  {% for post in site.categories.Intros %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a>
    <article class="archive-item">
      <p>{{ post.excerpt }}</p>
    </article>
  </li>
  {% endfor %}
</div>