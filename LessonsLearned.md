---
layout: page
permalink: /categories/Lessons
title: Lessons Learned
---

<div class="categoryContainer">
  {% for post in site.categories.Lessons %}
  <li>
    <h3 class="catTitle"><a href="{{ post.url }}">{{ post.title }}</a></h3> <br /> <span>{{ post.date | date_to_string }}</span>  
    <article class="archive-item">
      <p>{{ post.excerpt }}</p>
      <a href="{{ post.url }}">READ MORE</a>
    </article>
  </li>
  {% endfor %}
</div>