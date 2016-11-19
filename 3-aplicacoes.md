---
layout: aplicacao
title: Aplicações
menu-title: Aplicações
permalink: /aplicacoes/
---


{% for ap in site.aplicacoes %}
- {{ ap.title }}
{% endfor %}