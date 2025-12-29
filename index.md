---
layout: home
title: Início
---

<div style="text-align: center;">
    <img src="/assets/imagens/logo_gs_grande.png" alt="Cabeçalho" style="max-width: 40%; height: auto; border-radius: 8px;">
</div>


# Olá, eu sou o Guilherme Santos.

Sou desenvolvedor focado em **Sistemas Embarcados, Firmware e Hardware**. Este site é o meu "jardim digital" — um lugar onde documento meus projetos, compartilho aprendizados técnicos (como as andanças pelo G-Code) e publico alguns pensamentos sobre a vida.

---

## 🛠️ No que eu trabalho
* **Firmware:** Desenvolvimento em C/C++ para microcontroladores (Bare metal e RTOS).
* **Hardware:** Design de placas de circuito impresso e prototipagem.
* **Software:** Desenvolvimento de ferramentas de suporte e integração.

## 🚀 Experiências e Aprendizados
 Recentemente, tive que mergulhar no mundo do **G-Code** para usinar peças mecânicas para um projeto — uma prova de que na engenharia, o aprendizado nunca para.

---

## 📝 Últimas Notas e Reflexões
*Abaixo você encontrará meus posts mais recentes (posts da pasta `_posts` aparecerão aqui automaticamente):*

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <span>{{ post.date | date: "%d/%m/%Y" }}</span>
    </li>
  {% endfor %}
</ul>

<small>[Ver todos os posts](/blog)</small>

---

## 📬 Contato
Se você quiser conversar sobre firmware, hardware ou qualquer outro assunto aleatório:
* [LinkedIn](https://www.linkedin.com/in/SEU_USER)
* [GitHub](https://github.com/SEU_USER)
* Email: guilherme@santos.dev.br (exemplo)
