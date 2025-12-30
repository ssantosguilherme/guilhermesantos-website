---
layout: page
title: Filosofias
permalink: /filosofias/
---

### Por enquanto, pensamentos jogados sem muita organização

"Na cidade, as arquiteturas locais, os padrões de movimento e o comportamento chamam atenção; na natureza, a reflexão recai sobre o estado inicial e bruto da forma."

"Críticas construtivas são as principais oportunidades para melhoria contínua. Os elogios são bem-vindos, desde que não se tornem uma armadilha que leve ao conforto estagnado."

"Absolutamente tudo possui margem para melhoria, embora, no âmbito profissional e comercial, fatores externos determinem a real necessidade de avanços de desenvolvimento."

"Qualidade precede a agilidade. Um resultado final é o reflexo direto da excelência aplicada em cada etapa do projeto; se as etapas são negligenciadas, o todo é comprometido. Frequentemente recorre à máxima: ‘Diz-se não ter tempo para fazer corretamente, mas é preciso encontrar tempo para fazer duas vezes’."

"O imediatismo contemporâneo geralmente é mal interpretado. Há casos em que a velocidade é atingida com a remoção de etapas fundamentais. A otimização de um processo é o que permite atingir resultados rápidos com qualidade, o que vai contra a tendência atual de sacrificar o rigor técnico em favor de uma entrega acelerada."

<ul>
  {% for item in site.filosofias %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
