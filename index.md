---
layout: page
title: Bem vindo!
tagline: Nova casa! Novas ideias!
---
{% include JB/setup %}

{% for post in site.posts %}
{{ post.title }}
======================
{{ post.date | date_to_string }}

{{ post.content }}

<!-- [{{ post.date | date_to_string }} - {{post.title}}]({{ BASE_PATH }}{{ post.url }} "TITLE") -->
{% endfor %}
