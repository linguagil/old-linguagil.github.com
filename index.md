---
layout: page
title: Bem vindo!
tagline: Nova casa! Novas ideias!
---
{% include JB/setup %}
A ideia principal do Grupo LinguÁgil é disseminar conhecimento
na área de Tecnologia da Informação (TI) em Salvador e na Bahia.
Para isso, incentiva alunos de universidades e faculdades
a buscarem sempre mais! Seja através de eventos, como o
Evento LinguÁgil que, somando suas três edições, já contou com
mais de mil participantes; seja divulgando e organizando
Coding Dojos nas instituições de ensino; seja participando e
apoiando eventos de TI em Salvador e cidades do estado:
o Grupo quer ver o cenário de TI do estado melhorar sempre mais e mais!
<br>
#### Últimos Posts ####

{% for post in site.posts limit:3 %}
[{{ post.date | date: "%d/%m/%Y" }} - {{post.title}}]({{ BASE_PATH }}{{ post.url }} "{{ post.title }}")
{% endfor %}

<div style="text-align: right">
    <a href="archive.html" title="Outros posts">Mais posts...</a>
</div>