---
layout: page
title: Aplicações
menu-title: Aplicações
permalink: /aplicacoes/
excerpt: >
  Estamos em todos os lugares! Desde o início da cadeia produtiva,
  até o transporte de materiais para os pontos de venda, nossos
  produtos estão presentes em todos os processos.
---

Estamos em todos os lugares!

Desde o início da cadeia produtiva, até o transporte de materiais para os pontos de venda, nossos produtos estão presentes em todos os processos. Atendemos diversos tipos de empresas, de colheitadeiras na zona rural a grandes siderúrgicas.

<div data-grid="wrap" class="wrapper square-grid">
{% for ap in site.aplicacoes %}
  {% capture ap_img %}
  {% assign crumbs = ap.url | split: "/" %}
  {{ "/img/" }}{{ crumbs[1] }}/{{ crumbs[2] }}{{ ".jpg" }}
  {% endcapture %}
  {% capture colorcycle %}{% cycle '', 'hero red' 'hero black', 'hero', 'hero grey', 'hero', '', 'hero red'  %}{% endcapture %}
  {% capture opcycle %}{% cycle '', 'opacity:.3;', 'opacity:.2;'  %}{% endcapture %}
  <div data-cell class="square {{ colorcycle }}">
    <div class="square-bg" style="background-image: url('{{ ap_img | strip }}'); {{ opcycle }}"></div>
    <p><a href="{{ site.baseurl }}{{ ap.url }}">{{ ap.title }}</a></p>
  </div>
{% endfor %}
</div>