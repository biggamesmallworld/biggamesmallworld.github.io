---
layout: page
permalink: /categories/
title: Categories
---

<div class="container">
    <!--Row with three equal columns-->
    <div class="row">
        {% for category in site.categories %}
            <div class="catContainer">
                <a class="col-md-4 archive-group" href="{{ site.baseurl }}{{ category_name }}">
                    {% capture category_name %}{{ category | first }}{% endcapture %}
                    <div id="#{{ category_name | slugize }}"></div>
                    <h3 class="category-head">{{ category_name }}</h3>
                    <p name="{{ category_name | slugize }}"></p>
                </a>
            </div>
        {% endfor %}
    </div>
</div>