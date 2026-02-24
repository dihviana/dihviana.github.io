---
layout: default
title: Home
---

# Bem-vindo ao meu Portfólio de Security

Aqui organizo minhas análises sobre eventos e tendências de Cybersecurity.

### Artigos Recentes
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%d/%m/%Y" }})
{% endfor %}
