---
layout: page
permalink: /categories/Romance
title: Romantic Mishaps
---

<div class="categoryContainer">
  {% for post in site.categories.Romance %}
  <li>
    <h3 class="catTitle"><a href="{{ post.url }}">{{ post.title }}</a></h3> <br /> <span>{{ post.date | date_to_string }}</span>
    <article class="archive-item">
      <p>{{ post.excerpt }}</p>
      <a href="{{ post.url }}">READ MORE</a>
    </article>
  </li>
  {% endfor %}
</div>