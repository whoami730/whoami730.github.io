---
title: My Blogs
permalink: /blog
---

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}" class="post-preview">{{ post.title }}</a>
    {{ post.excerpt }}
  </li>
  {% endfor %}
</ul>

