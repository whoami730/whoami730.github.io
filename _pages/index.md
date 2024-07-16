---
permalink: /
---

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}"><b>{{ post.title }}</b></a>
    <small>{{ post.excerpt }}</small>
  </li>
  {% endfor %}
</ul>
