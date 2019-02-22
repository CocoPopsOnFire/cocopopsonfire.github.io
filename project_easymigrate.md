---
layout: page
title: EasyMigrate Dev Blog
subtitle: WIP
---

<ul>
  {% for post in site.posts %}
    <li>
        {% if post.catagories == easymigrate %}
        <h2>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </h2>
        {{ post.excerpt }}
        {% endif %}
    </li>
  {% endfor %}
</ul>
