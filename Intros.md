---
layout: page
permalink: /categories/Intros
title: Intros
---
<div class="categoryContainer">
  {% for post in site.categories.Intros %}
  <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</div>