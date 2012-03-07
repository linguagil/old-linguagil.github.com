---
layout: page
title: Bem vindo!
tagline: Nova casa! Novas ideias!
---
{% include JB/setup %}
<br>
#### Nossos Posts ####

{% for post in site.posts %}
* [{{ post.date | date_to_string }} - {{post.title}}]({{ BASE_PATH }}{{ post.url }} "TITLE")
{% endfor %}
