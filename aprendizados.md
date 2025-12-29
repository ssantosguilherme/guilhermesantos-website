---
layout: page
title: Aprendizados
permalink: /aprendizados/
---

### Aprendizados profissionais gerais
Aqui compartilho coisas que preciso aprender no meio do caminho para finalizar algum projeto.

<ul>
  {% for item in site.aprendizados %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
