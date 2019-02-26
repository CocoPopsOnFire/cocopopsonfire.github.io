---
layout: page
title: EasyMigrate Dev Blog
subtitle: WIP
---

<ul>
  {% for post in site.catagories.easymigrate %}
    <li>
        <h2>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </h2>
        {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
