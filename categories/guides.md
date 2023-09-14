---
layout: page
title: Guides
permaulnk: /blog/categories/guides/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.guides %}
 <ul class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></ul>
{% endfor %}
</div>