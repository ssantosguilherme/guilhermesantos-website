---
layout: page
title: Posts
permalink: /posts/
---

### Experiências profissionais
Aqui compartilho alguns projetos de bons resultados.

<ul>
  {% for item in site.posts %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
