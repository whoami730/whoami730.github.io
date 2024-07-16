---
permalink: /
---

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}"><b>{{ post.title }}</b></a>
    <br>
    <small>{{ post.excerpt }}</small>
  </li>
  {% endfor %}
</ul>
