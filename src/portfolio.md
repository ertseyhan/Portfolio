---
layout: page
title: Portfolio
---

<ul>
  {% for post in collections.posts.resources %}
    <li>
      <a href="{{ post.relative_url }}">{{ post.data.title }}</a>
    </li>
  {% endfor %}
</ul>

---
