---
layout: page
title: Filosofias
permalink: /filosofias/
---

### Pensamentos gerais
Aqui compartilho coisas que penso da vida, opiniões, pontos de vista, etc...

<ul>
  {% for item in site.filosofias %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
