---
layout: product
title:  Blog
---

  <ul class="posts">
    {% for post in site.categories.blog %}
      <li><span>{{ post.date|date: "%Y-%m-%d"  }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>


