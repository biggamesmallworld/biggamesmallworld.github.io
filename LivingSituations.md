---
layout: page
permalink: /categories/Living
title: Living Situations
---

<div class="categoryContainer">
  {% for post in site.categories.Living %}
  <li>
    <h3 class="catTitle"><a href="{{ post.url }}">{{ post.title }}</a></h3> <br /> <span>{{ post.date | date_to_string }}</span>
    <article class="archive-item">
      <p>{{ post.excerpt }}</p>
    </article>
  </li>
  {% endfor %}
</div>