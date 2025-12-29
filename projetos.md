---
layout: page
title: Projetos
permalink: /projetos/
---

### Projetos profissionais e pessoais
Aqui compartilho alguns projetos de bons resultados.

<ul>
  {% for item in site.projetos %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
