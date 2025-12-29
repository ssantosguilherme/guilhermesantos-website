---
layout: page
title: Entretenimento
permalink: /entretenimento/
---

### Jogos, livros, viagens, etc...
Aqui compartilho coisas que faço como forma de lazer.

<ul>
  {% for item in site.entretenimento %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
