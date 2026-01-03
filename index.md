---
layout: home
title: Home
---

# Em construção.

---

## Últimas atualizações.
*Abaixo você encontrará as últimas atualizações. (posts da pasta `_posts` aparecerão aqui automaticamente):*

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <span>{{ post.date | date: "%d/%m/%Y" }}</span>
    </li>
  {% endfor %}
</ul>

<small>[Ver todos os posts](/blog)</small>

---

## Contatos e perfis
* Email: guistech@gmail.com
* [Instagram](https://www.instagram.com/_guilhermessantos/)
* [Steam](https://steamcommunity.com/id/guilhermessantos/)
* [iRacing](https://members-ng.iracing.com/web/racing/profile?cust_id=1386783&tab=licenses)
* [LinkedIn](https://www.linkedin.com/in/guilhermesantosg2/)

