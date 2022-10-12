---
layout: page
title: Posts
---

<ul>
  {% for post in collections.posts.resources %}
    <li>
      <a style="border: none;" href="{{ post.relative_url }}">{{ post.data.title }}</a>
      <span style="color: rgba(0,0,0,.4);"><i><small>{{ post.data.date | date: "%d %B, %Y" }}</small></i></span>
    </li>
  {% endfor %}
</ul>

---
