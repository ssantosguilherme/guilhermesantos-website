---
layout: page
title: Posts
permalink: /posts/
---

### Posts gerais
Aqui compartilho conhecimento que julgo ser importante para alguma coisa.

<ul>
  {% for item in site.posts %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
