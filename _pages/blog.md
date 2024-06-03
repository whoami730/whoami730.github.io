---
title: My Blogs
---

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>{{ post.excerpt }}</small>
  </li>
  {% endfor %}
</ul>

