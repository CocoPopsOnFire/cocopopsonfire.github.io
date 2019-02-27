---
layout: page
title: Game Dev Project 1
subtitle: Work in Progress using Unity/C#
---

<ul>
  {% for post in site.categories.wolfgame %}
    <li>
        <h2>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </h2>
        {{ post.excerpt }}
    </li>
  {% else %}
    <h2> There are no posts here! woops! </h2>
  {% endfor %}
</ul>
